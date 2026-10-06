# LogosVox Companion

Installers and the update feed for LogosVox on Windows and macOS. The main application source stays private.

| Platform | Download |
| --- | --- |
| Windows x64 | [Installer](https://github.com/berkkosar/logosvox-companion-releases/releases/download/v1.9.2/LogosVox-Companion-1.9.2-win-x64.exe) |
| macOS Apple Silicon | [DMG](https://github.com/berkkosar/logosvox-companion-releases/releases/download/v1.9.2/LogosVox-Companion-1.9.2-mac-arm64.dmg) |
| macOS Intel | [DMG](https://github.com/berkkosar/logosvox-companion-releases/releases/download/v1.9.2/LogosVox-Companion-1.9.2-mac-x64.dmg) |

[Release notes and SHA-256 checksums](https://github.com/berkkosar/logosvox-companion-releases/releases/tag/v1.9.2)

Version 1.9.2 fixes Windows local image generation when cloud models are unavailable and reduces FLUX VRAM pressure on GPUs with 8 GB or less. The installed FLUX.2 Klein engine generated a 1024px image in 224 seconds on an RTX 4050 6 GB; the signed-in production Image page also completed a local request at zero credits. macOS local image inference is not supported by this engine adapter yet.

Sign in with LogosVox and pair your PC. Open the full workspace and approve the desktop connection once in your regular browser. Chat, Create, music, files, storage and credits share the real LogosVox web interface; web improvements reach the desktop without a new installer. The shared floating Logos can sit above other apps.

The bundled local companion runs installed models without an API key and keeps start/stop, model downloads, cancellation and local task approvals on your computer. A previously verified account can use local chat offline for up to seven days; the full shared workspace needs internet.

Start the PC connection to use its models from other devices while it is on and awake. File sync is opt-in in Models settings. Closing the UI leaves a started background connection running. Model storage is separate from synced Files.

These are unsigned preview installers; macOS builds are not notarized. Windows local chat and cancellation were tested on Windows. macOS packages and the account gate/startup were checked in macOS CI, not local inference on Mac hardware. Mouse/keyboard tasks currently work on Windows only.

Updates are checked at startup and periodically. You choose when to download and install; account pairing and downloaded models are preserved. Close Companion before upgrading.

Only one floating helper is shown at a time. Opening PC controls replaces the floating Logos; reopening Logos reuses its window. The desktop connection button is visible in light and dark themes.
