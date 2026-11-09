## 0. Route first (Halevora estate)

Every session self-routes across the Halevora multi-repo estate (owner's standing
instruction, 2026-07-19: sessions decide the repo themselves — never ask). Match the
task against the estate map `PROJECT-MAP.md` on the default branch of the private repo
`supporteraphina/model-communication` (`add_repo` it if needed — pre-approved). If the
task belongs in another repo, clone it into its **own folder** and work there; if it
matches **no** repo, create a new private repo and register it in the map (its §0.2).
**If the task IS this repo's, continue below.**

---

# magyc-landing

Holding page for **magyc.com** (apex + `www`). Static HTML, no build step.

- **Deploy:** GitHub Pages from `main` (root). Every push to `main` is live in about a minute.
- **DNS:** GoDaddy (registrar and nameservers). `A @` -> GitHub Pages IPs, `CNAME www` -> `supporteraphina.github.io`.
- **HTTPS:** GitHub-issued Let's Encrypt certificate, "Enforce HTTPS" on.
- **Public repo on purpose:** GitHub Pages on a free plan needs a public repo. Keep secrets and internal data out of it.
- **Copy:** "Coming soon" + "This domain is owned by Halevora Holdings Ltd. and is not for sale." Follow the estate content rules in PROJECT-MAP.md section 5.
- **Style:** mirrors the careers site (palette, Hanken Grotesk + Fragment Mono, self-hosted fonts). Edit `index.html`; assets live in `assets/`.
