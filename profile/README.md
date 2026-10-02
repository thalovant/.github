<!--
GitHub organization profile: shown at https://github.com/thalovant.
Last edit: Claude Sonnet 5.5 - 2026-10-02 - Motive: Align the profile with thalovant.com (Daily Desk, private workspaces), list what is actually public, and drop claims the product pages do not make.
-->

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/thalovant-logo-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/thalovant-logo-light.png">
    <img src="assets/thalovant-logo-dark.png" alt="Thalovant" width="380">
  </picture>
</p>

<h3 align="center">Assistants, agents and apps, through public hubs and private workspaces.</h3>

<p align="center">
  <a href="https://thalovant.com"><strong>Website</strong></a>
  &nbsp;·&nbsp;
  <a href="https://dash.thalovant.com/showroom"><strong>Try Daily Desk</strong></a>
  &nbsp;·&nbsp;
  <a href="https://docs.thalovant.com"><strong>Docs</strong></a>
  &nbsp;·&nbsp;
  <a href="https://discord.gg/FcAM8XCD"><strong>Discord</strong></a>
</p>

---

Thalovant connects voice, web, API, agents, embedded devices and headless Linux
to one hub. Start in public with [Daily Desk](https://dash.thalovant.com/showroom),
no account needed and no personal memory stored. When it earns its place, move
to a private workspace with memory, clients, private skills, analytics, API and
MQTT.

Thalovant builds on [OpenVoiceOS](https://github.com/OpenVoiceOS) and
[HiveMind](https://github.com/JarbasHiveMind), and keeps its forks of their
components public.

## Build with Thalovant

| I want to | Start here |
| --- | --- |
| Talk to a hub from my own code | **SDKs:** [Python](https://github.com/thalovant/thalovant-python-sdk) · [Node.js / TypeScript](https://github.com/thalovant/thalovant-node-sdk) · [Go](https://github.com/thalovant/thalovant-go-sdk) · [Rust](https://github.com/thalovant/thalovant-rust-sdk) · [Swift](https://github.com/thalovant/thalovant-swift-sdk) · [Kotlin](https://github.com/thalovant/thalovant-kotlin-sdk) · [.NET](https://github.com/thalovant/thalovant-dotnet-sdk) |
| Put a hub on a microcontroller or single-board computer | [thalovant-embedded-c](https://github.com/thalovant/thalovant-embedded-c): ESP32, Zephyr, Linux SBCs |
| Let an AI agent run Thalovant | [thalovant-mcp](https://github.com/thalovant/thalovant-mcp): an MCP server for the control plane and hub runtime |
| Control my home by voice | [ha-thalovant](https://github.com/thalovant/ha-thalovant): the Home Assistant integration, installed through HACS |
| Write a skill | [thalovant-skillkit](https://github.com/thalovant/thalovant-skillkit) and the [skill guide](https://docs.thalovant.com/developers/writing-a-skill/) |
| Download the voice satellite | [thalovant-downloads](https://github.com/thalovant/thalovant-downloads) and the [install guide](https://docs.thalovant.com/manage/install-thalovant-voice/) |
| Add a language | [thalovant-languages](https://github.com/thalovant/thalovant-languages) |

## What is public, and what is not

Public here: the SDKs, the MCP server, the Home Assistant integration, the skill
kit, the language data, the downloads, and our forks of OpenVoiceOS and HiveMind
components. Each carries its own licence (MIT, Apache-2.0, GPL-3.0 or AGPL-3.0,
as the upstream project or the repository states).

Private for now: the control plane, the console, the operators, the runtime
images and the hosted skills. They run [thalovant.com](https://thalovant.com),
and what they do is documented at [docs.thalovant.com](https://docs.thalovant.com).

## Security and contact

Report a suspected vulnerability privately to
[hello@thalovant.com](mailto:hello@thalovant.com); the
[security policy](https://github.com/thalovant/.github/blob/main/SECURITY.md)
says what to include and what to expect. For anything else, write to the same
address or join the [Discord](https://discord.gg/FcAM8XCD).
