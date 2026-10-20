# Soggy Pools Umbrel Store

## Upcoming v0.2.103 — DigiByte Thaw Day readiness

- Upgrade the bundled DigiByte Core node from v9.26.5 to v9.26.7 in the AIO build image.
- Prepare for DigiByte mainnet Thaw Day activation at block 24,490,000.
- The same DigiByte node serves DGB SHA-256d and DGB Scrypt mining.
- Preserve the existing `/data` volume, payout settings, ports and app ID.

**Release gate:** The updated multi-architecture Docker image must first be built, verified and published. The store Compose image reference remains pinned to the previous published image until that gate passes. This branch is not ready to merge/deploy yet.

Add `https://github.com/SoggyHammyDev/soggy-pools-store` as a community app store in Umbrel.

- BTC, BCH, XEC, DGB SHA-256d and BCH2 solo pools
- Independent node selection and pruning
- Worker records, network metrics and Discord alerts

[Source and build workflow](https://github.com/SoggyHammyDev/soggy-pools-aio)

The store package tracks the published AIO release image. Preserve app ID `soggy-pools-aio` and the `/data` mount when updating. No source compilation runs on the user's Umbrel.

Keep GHCR image access public for installation without registry credentials. License text is included in COPYING; corresponding component sources remain available through the source repository and its pinned upstream references.
