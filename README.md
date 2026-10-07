# BVE audit viewer

Hosted page for the Browser Visual Editor audit trail. It contains no log data. It fetches `audit.enc` (encrypted) from this site and decrypts it in your browser with the password you type; the password never leaves your machine.

Generated from the BVE repository (`scripts/build-audit-page.mjs`). `audit.enc` is written by `scripts/audit-publish.mjs`.
