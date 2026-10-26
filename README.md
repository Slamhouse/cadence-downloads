# Cadence downloads

Local desktop dictation without a transcription subscription. This repository distributes generic installers, release notes, checksums and licenses. Application development is maintained separately. No personal vocabulary, settings, recordings or history is included.

**[Download Cadence and get started](https://cadence-desktop.amazing-free-9532.chatgpt.site)** — no GitHub or app account required.

Version **1.2.0** adds lifetime words spoken and speaking WPM for the last 30 days. Counts use original spoken transcripts; WPM uses recording time rather than processing speed. Available history is backfilled, with estimated timings from older recordings. Lifetime totals survive history cleanup; earlier deleted history cannot be reconstructed.

## Windows x64

1. Download the installer from [Releases](https://github.com/Slamhouse/cadence-downloads/releases).
2. Install and open Cadence. Download a speech model once; Parakeet Unified English is the recommended English starting point (about 731 MB).
3. Click into a text field, hold **Ctrl+Alt**, speak and release. **Escape** cancels.

Use **1.1.1 or newer** for the Windows launch fix. Installed Cadence retains one stable user profile and its own desktop launch identity; an older portable copy cannot intercept the installed shortcut. Upgrading updates existing desktop/Start Menu shortcuts. The release is checked with competing copies, repeated launches, and a forced-close/reopen test that preserves synthetic history, vocabulary and a downloaded speech model.

Optional local polish is a separate 2.74 GB download. Start with speech-only on modest laptops. A recent 16 GB Windows x64 laptop is a recommended pilot target, not a tested minimum requirement. Performance depends on the CPU, GPU and free memory.

These early Windows builds are unsigned. Follow your organization's software policy if Windows or IT blocks installation. Check the release's SHA256SUMS.txt to verify a downloaded file. No GitHub account is required to download these public release assets.

## Mac

Download the **Apple Silicon Mac pilot** DMG from [Releases](https://github.com/Slamhouse/cadence-downloads/releases). Requires an M-series Mac and macOS 14+. Drag Cadence into Applications, open it, grant Microphone and Accessibility, then hold **Control+Option**, speak and release. You can keep it in your Dock or create a desktop alias.

This test release is ad-hoc signed and is **not Apple notarized**. macOS may require approval for Cadence in Privacy & Security after the first launch attempt. Do not disable system security globally. The release includes a Mac quickstart and SHA256SUMS.txt. Test on your own Mac before wider rollout; physical microphone/shortcut/paste tests remain distinct from CI checks. Intel Macs are not included. Use 16 GB unified memory as a pilot starting point; try speech-only first on 8 GB.

## Local data

Installed Windows version 1.0.1 stores data in `%USERPROFILE%\.cadence`, consistently across launch routes. Upgrade recovery snapshots are retained in its `recovery` folder. Portable builds intentionally use their own adjacent `Data` folder. Back up the entire data folder to preserve your vocabulary, history and recordings.

Mac data is stored separately from the app at `~/Library/Application Support/com.slamhouse.cadence`. Replacing Cadence.app should preserve it. Back up that folder before upgrading a test build.

Speech recognition and built-in local polish run on the user's computer. Advanced cloud polish providers are optional and send text to the selected provider. Each user has separate data. Automatic learning from corrections in other apps is not currently implemented.

## Attribution

Cadence is independently maintained by Slamhouse and is based on [Handy](https://github.com/cjpais/Handy), under the MIT license. It is not affiliated with Wispr Flow. See [LICENSE](LICENSE) and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). The installer also includes the corresponding runtime/model license notices.
