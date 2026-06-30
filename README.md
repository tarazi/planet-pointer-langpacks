# Planet Pointer — Language Packs

Downloadable translation packs for the **Planet Pointer** app (an offline
AR-style star & planet finder).

Each file in [`lang-packs/`](lang-packs/) is a single JSON pack
(`{ code, v, strings, content }`) for one language. The app fetches a pack
on demand when you choose a non-bundled language, then caches it on the
device so it keeps working offline.

These are **translation strings only** — no app code or logic. They live in a
public repo so the app can download them; the application source stays private.

Served to the app from:
`https://raw.githubusercontent.com/tarazi/planet-pointer-langpacks/main/lang-packs/<code>.json`
