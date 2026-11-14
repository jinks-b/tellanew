# tellanew.com

The public site for Tell Anew: landing page, privacy policy, support page.
Served by GitHub Pages from the `main` branch, root folder.

No build step, no dependencies, no cookies. Three static pages and
one stylesheet. One exception to "no scripts" (the user's choice, 2026-11-14):
a few inline lines at the end of `how-it-works/index.html` make a tap on a
feature's silent loop play its full video with sound. It makes no network
calls and stores nothing. The privacy policy here is the published copy of
`PRIVACY_POLICY.md` in the (private) app repo; **if you edit one, edit both** —
App Review rejects a policy link that does not match the app.

The app reads this URL from `AppLinks.swift`.
