# cleartok-selectors

Remote-updatable CSS selectors for the ClearTTok iOS app (TikTok repost remover).

`selectors.json` is fetched by the app at launch and cached. If TikTok changes
its web DOM, update the selectors here and bump `version` — the app picks up the
new config on the fly, without an App Store release.

Format: see the app's `SelectorConfig` model. `selectors` are CSS selectors
(strings), never executed as code.

Raw URL used by the app:
`https://raw.githubusercontent.com/itpnews/cleartok-selectors/main/selectors.json`
