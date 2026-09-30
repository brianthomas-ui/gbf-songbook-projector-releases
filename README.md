# GBF Music release artifacts

This repository contains generated public downloads for GBF Music. It is **not** the application source repository.

| Need | Go to |
|---|---|
| Application source, database migrations, tests, and documentation | [brianthomas-ui/gbf-music](https://github.com/brianthomas-ui/gbf-music) |
| Official member and projector downloads | [music.gbf-blr.com/download](https://music.gbf-blr.com/download) |
| Web application | [music.gbf-blr.com](https://music.gbf-blr.com) |

## What is stored here

- Electron application archives
- Windows x64 projector downloads
- Mac arm64 and Mac x64 projector downloads
- signed Android APKs
- bundled mobile web layers
- stable update manifests used by installed applications

GitHub Releases are written by the release scripts in the source repository. `mobile/latest.json` is the stable mobile
manifest source. Do not hand-edit generated artifacts or use this repository for product development.

## Current public releases

- Desktop projector: `1.1.86`
- Android: `1.1.54`, version code `56`

The production release APIs are authoritative:

- [Desktop release manifest](https://music.gbf-blr.com/api/projector/release)
- [Mobile release manifest](https://music.gbf-blr.com/api/mobile/release)

Every published artifact is verified by declared byte count and SHA-256 before the source repository records a release
as complete.
