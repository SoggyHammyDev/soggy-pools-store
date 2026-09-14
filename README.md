# Soggy Pools Umbrel Store

Add `https://github.com/SoggyHammyDev/soggy-pools-store` as a community app store in Umbrel.

- BTC, BCH, XEC, DGB SHA-256d and BCH2 solo pools
- Independent node selection and pruning
- Worker records, network metrics and Discord alerts

[Source and build workflow](https://github.com/SoggyHammyDev/soggy-pools-aio)

The Scrypt development build is not listed here yet. Update the app version and image reference together only after its build and acceptance checks pass. Preserve app ID `soggy-pools-aio` and the `/data` mount when updating. No source compilation runs on the user's Umbrel.

Keep GHCR image access public for installation without registry credentials. License text is included in COPYING; corresponding component sources remain available through the source repository and its pinned upstream references.
