# BVE audit viewer

Hosted page for the Browser Visual Editor audit trail. It contains no log data of its own. It reads the encrypted logs under `logs/` (listed in `logs/index.json`, which the relay keeps up to date) from this site and decrypts them in your browser with the password you type; the password never leaves your machine.

The page is generated from the BVE repository (`scripts/build-audit-page.mjs`). The files under `logs/` are written by the audit relay.

`about.html` and `privacy.html` are the home page and privacy policy shown on the Google sign-in consent screen. `downloads/` holds the demo app for Chrome Web Store reviewers.
