<div align="center">

# Rosé Pine · Prism

**A rose rests in the hush of dawn; a pine holds the blue of night. Leave a little room for quiet.**

![Modes: light and dark](https://img.shields.io/badge/modes-light%20%2B%20dark-c4a7e7?labelColor=191724)
![Theme API: 0.2](https://img.shields.io/badge/Tine_theme_API-0.2-c4a7e7?labelColor=191724)
[![License: MIT](https://img.shields.io/badge/license-MIT-c4a7e7?labelColor=191724)](LICENSE)
[![Release downloads](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-rose-pine-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-rose-pine-prism/releases)

[Download theme.json](https://github.com/EllisMorrow/tine-theme-rose-pine-prism/releases/latest/download/theme.json) · [中文说明](README.zh-CN.md) · [Adaptation notes](docs/adaptation.md)

</div>

Rosé Pine Dawn and Moon share one Prism theme: warm cream paper by day, a muted violet-blue evening by night, with rose, pine and iris accents.

### Dark mode

![Rosé Pine · Prism in Tine dark mode](docs/rose-pine-dark.png)

### Light mode

![Rosé Pine · Prism in Tine light mode](docs/rose-pine-light.png)

*Actual Windows Tine screenshots supplied after testing. Both palettes are included in this package.*

## Install

1. Download [theme.json](https://github.com/EllisMorrow/tine-theme-rose-pine-prism/releases/latest/download/theme.json).
2. In Tine, open **Settings → Appearance → Theme packages → Select theme.json** and select the downloaded file.
3. Choose **Use colors**, then select **Light**, **Dark** or **System** mode.

Requires Tine Theme API **0.2** support. Existing `logseq/custom.css` and device accent settings may affect the result. This package supplies colors only; typography, layout, task markers and other roles outside the theme API remain host-controlled.

## Palette

| Role | Light | Dark |
| --- | --- | --- |
| Canvas | `#FAF4ED` | `#232136` |
| Sidebar | `#FFFaf3` | `#1e1c2e` |
| Body | `#464261` | `#E0DEF4` |
| Heading | `#464261` | `#E0DEF4` |
| Accent | `#907AA9` | `#C4A7E7` |
| Links | `#286983` | `#9CCFD8` |
| Tags | `#98566B` | `#ea9a97` |
| Mark background | `#F5E7C9` | `#393552` |

## Tested in Tine

The manifest passed the official theme checker. A Chromium fixture checked both complete token sets, mode switching and specified contrast pairs. The user supplied the real Windows light/dark screenshots above using Tine's public welcome graph. The visible headings, body, outlines, links, tags, inline code and reference panels are shown; mark highlights, selection behavior, Settings and other platforms are not established by these images. See [screenshot notes](docs/screenshots.md).

## Source and scope

Based on [Rosé Pine Dawn / Rosé Pine Moon](https://github.com/rose-pine/rose-pine-palette) at `92af52b465ab6e47437aca223c9b8d3009a2023b`, under MIT; see [LICENSE](LICENSE). Dawn and Moon are official Rosé Pine variants included in the Codex theme family and documented by the upstream palette project. Tine roles are mapped independently; the light text and tag adjustments are documented for readability on declared surfaces.

Independent community adaptation by **EllisMorrow**, developed with AI assistance (`aiDevelopment: primary`). No Codex program code, logo or bundled assets are included. No affiliation or endorsement is claimed.

Only the 21 supported literal color roles per mode are packaged. It does not claim pixel-for-pixel reproduction of Codex, or that all Tine-derived and opacity-dimmed text meets a contrast target. Check results and actual application coverage are recorded in [adaptation notes](docs/adaptation.md).

## Feedback

[Open an issue](https://github.com/EllisMorrow/tine-theme-rose-pine-prism/issues) with your Tine version, operating system, mode and a screenshot without private note content. The download badge counts GitHub Release asset downloads, not installations or unique users.
