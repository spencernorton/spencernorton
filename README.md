<p align="center">
  <a href="https://norvitech.com"><img alt="NorviTech Suite — open-source apps for the Linux desktop and the self-hosted stack" src="https://norvitech.com/assets/banner.svg" width="800"></a>
</p>

<p align="center">
  <a href="https://norvitech.com"><img alt="norvitech.com" src="https://img.shields.io/badge/norvitech.com-FD8024.svg"></a>
  <a href="https://buy.stripe.com/8x26oH2U44f65TRe574wM04"><img alt="Donate" src="https://img.shields.io/badge/donate-Stripe-635bff.svg?logo=stripe&logoColor=white"></a>
</p>

NorviTech is Spencer Norton’s collection of open-source software for the Linux
desktop, the self-hosted stack and the Nintendo GameCube. The product READMEs
show real workflows and explain installation, data handling and releases.

## See it in use

| Helios — preview an app while you work | XNote — write, create and format notes |
|---|---|
| <a href="https://github.com/spencernorton/helios"><picture><source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/spencernorton/helios/main/docs/demos/browser-preview-poster-7b5f9e81b75a.png"><img src="https://raw.githubusercontent.com/spencernorton/helios/main/docs/demos/browser-preview-09c48384e3ae.gif" width="420" alt="Helios previews a local app and attaches a screenshot to a chat."></picture></a> | <a href="https://github.com/spencernorton/xnote"><picture><source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/spencernorton/xnote/main/docs/demos/notes-still.png"><img src="https://raw.githubusercontent.com/spencernorton/xnote/main/docs/demos/notes.gif" width="420" alt="XNote creates and formats sticky notes in an isolated demonstration profile."></picture></a> |

These are recordings of the real applications with demonstration content.
Each product documents its capture sources and offers still images.

## The suite

| Product | What it is | Install | Licence |
|---|---|---|---|
| **[Helios](https://github.com/spencernorton/helios)** | A native Linux coding desktop for Claude Code, Codex, Gemini, Muse, Kimi and OpenRouter, with conversations, approvals, browser previews and Git review. | APT (Ubuntu 26.04) · source | [MIT](https://github.com/spencernorton/helios/blob/main/LICENSE) |
| **[DH-Waypoint](https://github.com/spencernorton/DH-Waypoint)** | A self-hosted BitTorrent DHT crawler and indexer for the \*arr stack. Descended from bitmagnet, it learns from what your \*arrs grab and serves its catalogue over Torznab, GraphQL and REST. | Docker Compose · source | [MIT](https://github.com/spencernorton/DH-Waypoint/blob/main/LICENSE) |
| **[Armiger](https://github.com/spencernorton/armiger)** | Local classification of torrent and media metadata, with ONNX inference and optional title matching and enrichment. | Docker Compose · Python | [Apache-2.0](https://github.com/spencernorton/armiger/blob/main/LICENSE) |
| **[XNote](https://github.com/spencernorton/xnote)** | Modern GTK4 sticky notes for GNOME. Descended from Xpad, with a colour picker, layout presets and Wayland-safe placement. | APT (Ubuntu 26.04) · source | [GPL-3.0-or-later](https://github.com/spencernorton/xnote/blob/main/COPYING) |
| **[XNote Placement](https://github.com/spencernorton/xnote-placement)** | Puts every XNote sticky note back where you left it. A GNOME Shell extension that restores each note's position, monitor and workspace on Wayland, where the app cannot do it itself. | APT (Ubuntu 26.04) · source | [GPL-3.0-or-later](https://github.com/spencernorton/xnote-placement/blob/main/LICENSE) |
| **[SnipSnap](https://github.com/spencernorton/snipsnap)** | Screenshot any region of any monitor on GNOME Wayland, with no permission dialog. A Qt 6 capture-and-annotate tool whose GNOME Shell extension draws the selection inside the compositor. Descended from Flameshot. | APT (Ubuntu 26.04) · source | [GPL-3.0-or-later](https://github.com/spencernorton/snipsnap/blob/main/LICENSE) |
| **[Conductor](https://github.com/spencernorton/conductor)** | A drop-in HDHomeRun tuner for Plex Live TV, backed by your own IPTV credentials. One Go service that pools provider slots, enriches the guide, and speaks the protocols Plex already trusts. | Docker Compose · source | [MIT](https://github.com/spencernorton/conductor/blob/main/LICENSE) |
| **[NorviOS](https://github.com/spencernorton/norvi-os)** | The NorviTech look for Ubuntu 26.04, from the boot splash to the window glass. A reversible layer over stock Ubuntu and GNOME 50, applied only through the override points Ubuntu provides, so updates keep working and one command puts the original back. | from source | [GPL-3.0-or-later](https://github.com/spencernorton/norvi-os/blob/main/LICENSE) |
| **[Indigo](https://github.com/spencernorton/indigo)** | A fork of Swiss for the Nintendo GameCube with the interface rebuilt. An animated Home, a poster library and game details, drawn in the console's own visual language. | SD card zip | [GPL-2.0-or-later](https://github.com/spencernorton/indigo/blob/main/LICENSE) |
| **[Road Track](https://github.com/spencernorton/roadtrack)** | What every car in the garage really costs, on top of LubeLogger. A running-cost dashboard, a finance tab and printable reports for the self-hosted LubeLogger vehicle tracker, added over its published image without forking it. | Docker Compose · source | [MIT](https://github.com/spencernorton/roadtrack/blob/main/LICENSE) |

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
- **No e-mail.** Bugs and ideas go to each repository's issues and
  Discussions; security reports go through GitHub private vulnerability
  reporting. That is deliberate.
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
  <a href="https://github.com/spencernorton/xnote">XNote</a> ·
  <a href="https://github.com/spencernorton/xnote-placement">XNote Placement</a> ·
  <a href="https://github.com/spencernorton/snipsnap">SnipSnap</a> ·
  <a href="https://github.com/spencernorton/conductor">Conductor</a> ·
  <a href="https://github.com/spencernorton/norvi-os">NorviOS</a> ·
  <a href="https://github.com/spencernorton/indigo">Indigo</a> ·
  <a href="https://github.com/spencernorton/roadtrack">Road Track</a> ·
  <a href="https://norvitech.com">norvitech.com</a>
</p>
