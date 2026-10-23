# Cadence downloads

Local desktop dictation without a transcription subscription. This repository distributes generic installers, release notes, checksums and licenses. Application development is maintained separately. No personal vocabulary, settings, recordings or history is included.

## Windows x64

1. Download the installer from [Releases](https://github.com/Slamhouse/cadence-downloads/releases).
2. Install and open Cadence. Download a speech model once; Parakeet Unified English is the recommended English starting point (about 731 MB).
3. Click into a text field, hold **Ctrl+Alt**, speak and release. **Escape** cancels.

Optional local polish is a separate 2.74 GB download. Start with speech-only on modest laptops. A recent 16 GB Windows x64 laptop is a recommended pilot target, not a tested minimum requirement. Performance depends on the CPU, GPU and free memory.

These early Windows builds are unsigned. Follow your organization's software policy if Windows or IT blocks installation. Check the release's SHA256SUMS.txt to verify a downloaded file. No GitHub account is required to download these public release assets.

## Mac

There is no Cadence Mac installer available yet. A separate, tested and signed Mac release is needed. The Windows installer does not run directly on macOS.

## Local data

Installed Windows version 1.0.1 stores data in `%USERPROFILE%\.cadence`, consistently across launch routes. Upgrade recovery snapshots are retained in its `recovery` folder. Portable builds intentionally use their own adjacent `Data` folder. Back up the entire data folder to preserve your vocabulary, history and recordings.

Speech recognition and built-in local polish run on the user's computer. Advanced cloud polish providers are optional and send text to the selected provider. Each user has separate data. Automatic learning from corrections in other apps is not currently implemented.

## Attribution

Cadence is independently maintained by Slamhouse and is based on [Handy](https://github.com/cjpais/Handy), under the MIT license. It is not affiliated with Wispr Flow. See [LICENSE](LICENSE) and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). The installer also includes the corresponding runtime/model license notices.
