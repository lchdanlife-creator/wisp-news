# wisp-news

Home-screen announcements for **Wisp: Desktop Widgets** (Steam).

- `home-feed.json` — the signed feed the app downloads (ECDSA P-256). The app shows it only if the signature matches the public key built into the app and its `version` is newer than what it already has.
- `home.json` — the unsigned source the feed is signed from.

The app sends a plain GET request with no cookies or identifiers. It can be turned off in Wisp → Settings → Permissions & Privacy → "Get Home announcements".
