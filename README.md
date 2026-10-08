# balatechnologies

The Bala Technologies LLC website, served by GitHub Pages from `main`. Plain HTML, no build step.

- `/` — company page
- `/uphill/` — Uphill Duo: Roll Ball Game
- `/uphill/support/` — App Store support URL
- `/uphill/privacy/` — App Store privacy policy URL. Keep it in step with
  `docs/PRIVACY.md` and `PrivacyPolicyView.swift` in the uphill-iOS repo.

## Custom domain

To serve the site at balatechnologies.info: add a `CNAME` file containing `balatechnologies.info`
(or set it under Settings → Pages), then at the registrar point the apex at GitHub Pages
(A records 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and `www` at
`eimanz.github.io` (CNAME). Only add the `CNAME` once the domain resolves: with it set, the
github.io address redirects to the domain.
