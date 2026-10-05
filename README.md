# LogosVox Companion downloads

[Download Windows or macOS](https://github.com/berkkosar/logosvox-companion-releases/releases/tag/v1.8.0) · [LogosVox settings](https://app.logosvox.com/settings?tab=models)

This repository distributes installer binaries, checksums and the desktop update manifest. The application source lives in a separate private repository.

Sign in with your LogosVox account and approve the computer code to use Companion. Existing paired computers verify their connection. Your local models run on your computer without an API key. Chat, model controls and shared file tasks work on Windows and macOS; mouse and keyboard tasks are currently Windows-only.

Companion checks for app updates on opening, every four hours and from Settings. Download the indicated installer, close Companion, and install the new version. Your models and pairing remain in place. Each release includes SHA256SUMS.txt. The updates.json file announces a version only after its installers are uploaded.

Preview packages are unsigned and macOS packages are not notarized. Windows local inference and cancellation have been tested. macOS CI checks package startup and account gating; real inference on Mac has not yet been verified.
