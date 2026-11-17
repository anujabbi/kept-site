# KEPT site

Marketing page for **KEPT (Keep Every Promise Today)** — Android habit-lock: apps stay locked until daily habits are done.

- Live: https://anujabbi.github.io/kept-site/
- Privacy (Play): https://anujabbi.github.io/kept-site/privacy-policy.html
- Closed testing: https://play.google.com/apps/testing/com.zenai.kept

Audience: high school through ~30s, phone addiction / habit follow-through (not parental control).

Copy on this site should match the app in [anujabbi/kept](https://github.com/anujabbi/kept): one to ten daily habits, tap-done or photo proof (no timer), no buddy or Duo. See `docs/growth/PLAY-LISTING.md` in that repo.

To collect waitlist emails, set `WAITLIST_ENDPOINT` in `index.html` to any endpoint that accepts a JSON POST with an `email` field (for example a Formspree form URL). Until then the form links to a GitHub issue.
