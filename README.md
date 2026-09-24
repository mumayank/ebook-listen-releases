# Stories releases

Public release artifacts + update manifest for **Stories**, an offline-first
EPUB reader and local-TTS audiobook player.

Source code lives in a private repository.

## Downloads

See the [Releases](../../releases) tab, or the [download page](https://mumayank.github.io/stories-releases/).
Web build: https://mumayank.github.io/stories-releases/app/

## Update manifest

The app reads [`latest.json`](./latest.json) to check for updates. `scripts/release-local.sh`
rewrites it on every release.

## Platforms

| Platform | Delivery | In-app update |
|---|---|---|
| Android | signed APK from Releases | download + install (FileProvider) |
| macOS | DMG | download + open installer |
| Linux | .deb | download + open installer |
| iOS | unsigned build (sideload) | store link only (not published yet) |
| Web | Wasm app at `/app/` | reload |

Windows is not shipped (no MSI cross-compile from macOS).
