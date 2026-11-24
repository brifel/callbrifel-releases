# CallBrifel Public Releases & Update Manifests

This repository contains **release metadata and update manifests only** for the CallBrifel desktop application (`https://github.com/brifel/callbrifel-releases`).

## Layout

- [`latest.json`](./latest.json) — Authoritative latest release manifest queried by CallBrifel's Wails v3 self-updater.
- `releases/<VERSION>/manifest.json` — Version-pinned release manifest containing per-platform download URLs and SHA-256 digests.
- `releases/<VERSION>/checksums.txt` / `SHA256SUMS` — SHA-256 checksums for all release artifacts.

Binary installers and update archives (`.dmg`, `.app.zip`, `-installer.exe`, `.zip`, `.tar.gz`, `.deb`) are attached directly as assets on the corresponding **GitHub Release** tag (`v<VERSION>`).
