# Sidekick optional tool downloads

Optional media and isolated-analysis packs for the separate small Sidekick development installer. These are Apple Silicon / macOS 15+ development artifacts.

Use Sidekick Setup to install only the capabilities you choose. The installer checks its signed component catalog, download size and SHA256, installed file inventory, and applicable native-code policy before activating a component. Installed verified components are reused.

[Tool-pack development release](https://github.com/bhushan6/sidekick-downloads/releases/tag/toolpacks-2026-11-06-v1)

| Pack | Download bytes |
| --- | ---: |
| Media: FFmpeg / FFprobe | 35,262,083 |
| Analysis host tools | 256,308,786 |
| Analysis VM base | 1,552,032,930 |
| Analysis image | 1,487,520,184 |

The release includes `assets.json` and `SHA256SUMS`. Each tool archive carries its supplied third-party source archives, licenses and notices. Third-party components retain their respective licenses; this repository does not relicense them.

This repository contains optional tool artifacts, not the private Sidekick application source, signing keys, provider profiles, chat history or user projects. A tool-pack download does not grant a license to the Sidekick application or access to an AI provider account.

These packs are not a production or commercial-release certification. See the development release notes and bundled notices for the existing Docker-init static-libc build-attestation limitation.
