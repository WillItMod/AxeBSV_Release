# AxeBSV Release (public)

This repo contains the **public** Umbrel/5tratumOS recipe files for AxeBSV.

It must **not** contain any application source code.

The private build repo publishes the UI image to GHCR; the recipe points at that image and at the node/pool images.

## Current status

- DEV store recipe is mirrored into `WillItMod/umbrel-dev-community-store` under `willitmod-dev-bsv/`.
- The BSV node image used initially is `bitcoinsv/bitcoin-sv` (amd64 only). arm64 support will be added later via a multi-arch GHCR node image.
