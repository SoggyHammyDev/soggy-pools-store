# Soggy Pools Umbrel Store

## Upcoming v0.2.103 — DigiByte Thaw Day readiness

- Upgrade DigiByte Core from v9.26.5 to v9.26.7 for activation at block 24,490,000.
- The bundled DigiByte node is shared by DGB SHA-256d and Scrypt mining.
- Preserve the existing data mount, application ID, mining ports and payout settings.
- Publication gate: confirm the AMD64 and ARM64 image builds and publish the v0.2.103 GHCR image before bumping the live Umbrel manifest and Compose image reference.

Add `https://github.com/SoggyHammyDev/soggy-pools-store` as a community app store in Umbrel.

- BTC, BCH, XEC, DGB SHA-256d and BCH2 solo pools
- Independent node selection and pruning
- Worker records, network metrics and Discord alerts

[Source and build workflow](https://github.com/SoggyHammyDev/soggy-pools-aio)

The store package tracks the published AIO release image. Preserve app ID `soggy-pools-aio` and the `/data` mount when updating. No source compilation runs on the user's Umbrel.

Keep GHCR image access public for installation without registry credentials. License text is included in COPYING; corresponding component sources remain available through the source repository and its pinned upstream references.
