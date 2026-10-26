# Sawt Updates

Public update feed and signed release packages for [Sawt](https://github.com/Hmzeid/Sawt).

- `updates.json` is the signed update manifest consumed by Sawt.
- Release packages are attached to the tags in this repository.
- The app verifies the Ed25519 signature in `updates.json` and the SHA-256 of the downloaded DMG before installing.
