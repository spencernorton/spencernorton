<p align="center">
  <a href="https://norvitech.com"><img alt="NorviTech Suite — open-source software for Linux, self-hosting, AI and GameCube" src="https://norvitech.com/assets/banner.svg" width="800"></a>
</p>

<p align="center">
  <a href="https://norvitech.com"><img alt="norvitech.com" src="https://img.shields.io/badge/norvitech.com-FD8024.svg"></a>
  <a href="https://buy.stripe.com/8x26oH2U44f65TRe574wM04"><img alt="Donate" src="https://img.shields.io/badge/donate-Stripe-635bff.svg?logo=stripe&logoColor=white"></a>
</p>

NorviTech is Spencer Norton’s collection of open-source software for the Linux
desktop, self-hosting, AI and the Nintendo GameCube. Each project documents how
to install it, how it handles data and where to find releases.

[Ubuntu packages](https://norvitech.com/#install) · [AI models](https://norvitech.com/ai-models/) · [GitHub repositories](https://github.com/spencernorton?tab=repositories)

## See it in use

| Helios — preview an app while you work | XNote — write, create and format notes |
|---|---|
| <a href="https://github.com/spencernorton/helios"><picture><source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/spencernorton/helios/main/docs/demos/browser-preview-poster-7b5f9e81b75a.png"><img src="https://raw.githubusercontent.com/spencernorton/helios/main/docs/demos/browser-preview-09c48384e3ae.gif" width="420" alt="Helios previews a local app and attaches a screenshot to a chat."></picture></a> | <a href="https://github.com/spencernorton/xnote"><picture><source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/spencernorton/xnote/main/docs/demos/notes-still.png"><img src="https://raw.githubusercontent.com/spencernorton/xnote/main/docs/demos/notes.gif" width="420" alt="XNote creates and formats sticky notes in an isolated demonstration profile."></picture></a> |

These are recordings of the real applications with demonstration content.
Each product documents its capture sources and offers still images.

## The suite

| Product | What it is | Install | Licence |
|---|---|---|---|
| **[Helios](https://github.com/spencernorton/helios)** | A native Linux desktop for coding agents, with approvals, browser previews and Git review. | APT (Ubuntu 26.04) · source | [MIT](https://github.com/spencernorton/helios/blob/main/LICENSE) |
| **[DH-Waypoint](https://github.com/spencernorton/DH-Waypoint)** | A self-hosted BitTorrent DHT crawler and Torznab indexer for the \*arr stack. | Docker Compose · source | [MIT](https://github.com/spencernorton/DH-Waypoint/blob/main/LICENSE) |
| **[Armiger](https://github.com/spencernorton/armiger)** | Local ONNX classification and enrichment for torrent and media metadata. | Docker Compose · Python | [Apache-2.0](https://github.com/spencernorton/armiger/blob/main/LICENSE) |
| **[Arrmes](https://github.com/spencernorton/arrmes)** | A local model that routes and verifies tool calls for self-hosted media stacks. | Python · MLX · GGUF | [Apache-2.0](https://github.com/spencernorton/arrmes/blob/main/LICENSE) |
| **[Endexis](https://github.com/spencernorton/endexis)** | A clinical reporting SQL and CCL compiler with a local assistant for Oracle Health. | Python · Hugging Face | [Apache-2.0](https://github.com/spencernorton/endexis/blob/main/LICENSE) |
| **[XNote](https://github.com/spencernorton/xnote)** | Native GTK4 sticky notes for GNOME, with encrypted backups. | APT (Ubuntu 26.04) · source | [GPL-3.0-or-later](https://github.com/spencernorton/xnote/blob/main/COPYING) |
| **[XNote Placement](https://github.com/spencernorton/xnote-placement)** | A GNOME Shell extension that restores XNote’s positions, monitors and workspaces on Wayland. | APT (Ubuntu 26.04) · source | [GPL-3.0-or-later](https://github.com/spencernorton/xnote-placement/blob/main/LICENSE) |
| **[SnipSnap](https://github.com/spencernorton/snipsnap)** | A screenshot and annotation tool for GNOME Wayland. | APT (Ubuntu 26.04) · source | [GPL-3.0-or-later](https://github.com/spencernorton/snipsnap/blob/main/LICENSE) |
| **[Conductor](https://github.com/spencernorton/conductor)** | A self-hosted HDHomeRun emulator that brings IPTV to Plex Live TV. | Docker Compose · source | [MIT](https://github.com/spencernorton/conductor/blob/main/LICENSE) |
| **[NorviOS](https://github.com/spencernorton/norvi-os)** | Reversible Ubuntu and GNOME customizations, from the boot splash to the desktop. | APT (Ubuntu 26.04) · source | [GPL-3.0-or-later](https://github.com/spencernorton/norvi-os/blob/main/LICENSE) |
| **[Indigo](https://github.com/spencernorton/indigo)** | A fork of Swiss with a visual game library for the Nintendo GameCube. | SD card zip | [GPL-2.0-or-later](https://github.com/spencernorton/indigo/blob/main/LICENSE) |
| **[Road Track](https://github.com/spencernorton/roadtrack)** | Running costs, vehicle finance and printable reports for LubeLogger. | Docker Compose · source | [MIT](https://github.com/spencernorton/roadtrack/blob/main/LICENSE) |

Each product’s README is its installation guide. Release packages, source builds,
container images and console builds have different requirements; follow the
guide for the product you choose.

[NorviOS](https://github.com/spencernorton/norvi-os) brings the GNOME components
together. [Armiger Connectors](https://github.com/spencernorton/Armiger-Connectors)
connects the classifier to other indexers, and
[CubeBrowser](https://github.com/spencernorton/cubebrowser) provides the separate
GameCube browser used by Indigo.

## How these repositories work

- **Development on GitHub.** Open a pull request in the relevant repository.
  Changes are reviewed and merged there; each product’s CONTRIBUTING.md explains
  its checks and release process.
- **Show the software.** UI projects lead with recordings of real interactions;
  headless tools explain their data flow with architecture diagrams. Still images
  accompany the recordings for reduced-motion viewing.
- **Support and security.** Follow the project’s support links for bugs and
  ideas. Use GitHub’s private vulnerability reporting for security issues.
- **Forks stay honest.** DH-Waypoint and XNote keep their upstream licences,
  notices and authors; each README says exactly what is upstream's and what
  is new.

## Support the work

If one of these saves you time, you can
[support its development](https://buy.stripe.com/8x26oH2U44f65TRe574wM04).
The whole suite, with links to every product, lives at
[norvitech.com](https://norvitech.com).

---

<p align="center">
  <a href="https://github.com/spencernorton/helios">Helios</a> ·
  <a href="https://github.com/spencernorton/DH-Waypoint">DH-Waypoint</a> ·
  <a href="https://github.com/spencernorton/armiger">Armiger</a> ·
  <a href="https://github.com/spencernorton/arrmes">Arrmes</a> ·
  <a href="https://github.com/spencernorton/endexis">Endexis</a> ·
  <a href="https://github.com/spencernorton/xnote">XNote</a> ·
  <a href="https://github.com/spencernorton/xnote-placement">XNote Placement</a> ·
  <a href="https://github.com/spencernorton/snipsnap">SnipSnap</a> ·
  <a href="https://github.com/spencernorton/conductor">Conductor</a> ·
  <a href="https://github.com/spencernorton/norvi-os">NorviOS</a> ·
  <a href="https://github.com/spencernorton/indigo">Indigo</a> ·
  <a href="https://github.com/spencernorton/roadtrack">Road Track</a> ·
  <a href="https://norvitech.com">norvitech.com</a>
</p>
