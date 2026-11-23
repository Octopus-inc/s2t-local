# SEO landing — release checklist (not published yet)

Draft static site in docs/ for GitHub Pages, not a new executable application release.

- Publishing is NOT approved just because this branch exists.
- GitHub Pages target planned: https://octopus-inc.github.io/s2t-local/
- Before enabling: verify Pages is not already configured; confirm branch/folder selection and that no paid CI/billing changes will occur.
- After explicit permission: review/merge docs/ into public main if source is main/docs, OR configure the approved source branch/docs. Avoid publishing from the draft branch unintentionally.
- Confirm deployed root, /interviews/, /meetings/, /style.css, and /sitemap.xml each return 200.
- Verify visible canonical links and sitemap URLs agree with the *actual* deployed host and path; adapt before publish if using a custom domain.
- GitHub Pages is project-scoped: robots.txt at /s2t-local/ is not the host-root robots.txt, so none is included.
- Content links to exact validated v0.1.3 pre-release; do NOT change ZIP or its SHA.
- Avoid claiming cloud processing, automatic notes, universal hardware compatibility, or fully signed Windows installer.
- No user tracking/analytics scripts in this draft. Count GitHub asset downloads separately from internal tests; connect Search Console and Yandex Webmaster only after deployment, with explicit site verification.
- First acquisition test: search impressions, landing visits if measurable, download clicks with a deliberately selected privacy-respecting analytics option, user-reported first-run successes, and opt-in feedback. Do not conflate download clicks with installations.
- SEO assumptions are unverified: keywords need Yandex Wordstat / Search Console data; no traffic guarantees.
