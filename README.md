<p align="center">
  <strong>Gyra</strong> · pronounced <em>Gü-ra</em> (not “Ji-ra”)<br/>
  Bring-your-own-keys macOS agent runtime
</p>

<p align="center">
  <img alt="platform" src="https://img.shields.io/badge/platform-macOS-E8B86D?style=flat-square" />
  <img alt="distribution" src="https://img.shields.io/badge/distribution-DMG-6EE7C5?style=flat-square" />
</p>

---

## What it is

**Gyra** is a local macOS desktop app for running AI agents with **your** API keys. It sells the **runtime and UX**, not a model marketplace.

- Create and configure bots in a few steps
- Pick a model per bot — lists grouped by the keys you saved
- API keys stay in **macOS Keychain**, not in bot configs or chat transcripts
- One active chat session per bot in the early product

Tagline: **Runtime, not the model.**

## Who it's for

Indie and solo builders who want a calm, dark-first Mac agent shell: switch providers without rewriting prompts, keep keys off disk in plain text, and run a local app first.

## Download

**[Go to Releases →](https://github.com/gary-quinn/gyra-releases/releases)**

1. Open the latest release for your channel (stable or pre-release).
2. Download the `.dmg` for macOS.
3. Open the disk image and drag **Gyra** into Applications.
4. On first launch, macOS may warn that the app is from an unidentified developer — open **System Settings → Privacy & Security** and choose **Open Anyway** if needed.

Pre-releases (`beta`, `alpha`, `rc` tags) are for early testing. Prefer the latest non–pre-release build for day-to-day use.

## Requirements

- **macOS** (Apple Silicon or Intel, per the release you download)
- API keys for the providers you want to use (Anthropic, OpenAI, DeepSeek, OpenRouter, NVIDIA NIM, and others as supported in the app)

Gyra does not host models or sell API access. You bring your own keys.

## Security notes

- Keys are stored in the macOS Keychain on your machine.
- This repository only hosts **installers** — not source code, issue tracking, or internal product docs.
- Verify downloads from this repo’s Releases page only.

## Support

This repo is for distribution. For product feedback or bug reports, use the channels provided by the Gyra team (not this repository’s Issues tab unless explicitly enabled).

## License

Gyra is **proprietary software**. Source code is not published.

Installers in [Releases](https://github.com/gary-quinn/gyra-releases/releases) are licensed for personal or internal use only — not for redistribution, reverse engineering, or resale. See [LICENSE](LICENSE) for the full terms.
