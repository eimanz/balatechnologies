# balatechnologies

The Bala Technologies LLC website, served by GitHub Pages from `main`. Plain HTML, no build step.

- `/` — company page
- `/uphill/` — Uphill: Bowling Arcade Game
- `/uphill/support/` — App Store support URL
- `/uphill/privacy/` — App Store privacy policy URL. Keep it in step with
  `docs/PRIVACY.md` and `PrivacyPolicyView.swift` in the uphill-iOS repo.
- `/yehdor/` — YehDor (party games). `/yehdor/support/` and `/yehdor/privacy/` are its App Store
  support and privacy policy URLs; keep the policy in step with `PRIVACY.md` in the Bazna repo.

## Custom domain

Served at https://balatechnologies.site (registered at Namecheap; the `CNAME` file and the Pages
setting name it). Namecheap → Advanced DNS holds:

- A `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153 (GitHub Pages)
- CNAME `www` → `eimanz.github.io.`

The old https://eimanz.github.io/balatechnologies/ addresses redirect to the domain, so links
already in App Store Connect keep working.
