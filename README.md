# Ebook.listen releases

Public release artifacts + update manifest for **Ebook.listen**, an offline-first
EPUB reader and local-TTS audiobook player.

Source code lives in a private repository.

## Downloads

See the [Releases](../../releases) tab for the latest APK, macOS DMG, Windows
installer and Linux AppImage.

## Update manifest

The app reads [`latest.json`](./latest.json) to check for updates. Bump the
`version` and artifact URLs when publishing a release.

## Platforms

| Platform | Delivery | In-app update |
|---|---|---|
| Android | APK from Releases | download + install (FileProvider) |
| macOS | DMG | download + open installer |
| Windows | MSI/EXE | download + open installer |
| Linux | AppImage/Deb | download + open installer |
| iOS | App Store / TestFlight | store link only |
