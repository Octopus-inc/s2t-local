# S2T Local SEO landing — approved publication checklist

User explicitly approved public GitHub Pages publication in the current conversation on 2026-11-23. Authorization applies to the static landing site only, not a new executable release, paid CI, billing, or changes to private sources.

## Proposed GitHub Pages source

- Repository: https://github.com/Octopus-inc/s2t-local (public).
- Source: **Deploy from a branch**.
- Branch: **feature/seo-landing-20261123**.
- Folder: **/docs**.
- Save.
- Expected project URL (only after deployment succeeds): https://octopus-inc.github.io/s2t-local/.
- No PR or merge into main is necessary for this source selection. No custom GitHub Actions workflow has been added.
- GitHub's automatic Pages build/deploy may appear in Actions; public repository standard hosted Actions are not billed. Do not change CI billing or run paid workflows.
- The connected GitHub tool does not expose the repository Pages settings mutation; an authorized maintainer must perform this one configuration operation in GitHub's browser UI. Do not claim that a site is live until verified.

## Live QA (after GitHub reports a successful deployment)

1. GET /s2t-local/, /s2t-local/interviews/, /s2t-local/meetings/, /s2t-local/style.css, /s2t-local/sitemap.xml. Confirm all return HTTP 200 with expected content (no custom domain assumed).
2. Verify titles, meta descriptions, canonical URLs and the exact indexable URLs in sitemap. Check links to v0.1.3 releases and privacy policy.
3. Inspect narrow/mobile layout, keyboard navigation, readable text and no unexpected analytics requests.
4. Connect Yandex Webmaster and Google Search Console only after the site is live, using explicit account verification.

## Security and growth constraints

- GitHub Pages is project-scoped: a robots.txt under /s2t-local/ would not act as host-root robots.txt, so no such file is included.
- Keep published v0.1.3 ZIP and SHA unchanged. No cloud processing, auto-generated meeting notes, guaranteed speeds, universal hardware support, or digitally signed EXE claims.
- No client-side trackers are included in this draft. Report visits, download clicks, downloads and successful installations as distinct metrics; do not infer installs from GitHub asset download count.
- SEO keyword demand remains unverified pending Yandex Wordstat and real search analytics. No traffic guarantee.
