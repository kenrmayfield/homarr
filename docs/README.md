<!-- Project Title -->
[![Banner](./banner.png)](https://homarr.dev/)

<!-- Badges -->
<p align="center">
<img src="https://img.shields.io/github/stars/homarr-labs/homarr?label=%E2%AD%90%20Stars&style=flat-square?branch=master&kill_cache=1%22">
<a href="https://github.com/homarr-labs/homarr/releases/latest">
  <img alt="Latest Release (Semver)" src="https://img.shields.io/github/v/release/homarr-labs/homarr?label=%F0%9F%9A%80%20Release">
</a>
<a href="https://github.com/homarr-labs/homarr/actions/workflows/deployment-docker-image.yml">
  <img title="Docker CI Status" src="https://github.com/homarr-labs/homarr/actions/workflows/deployment-docker-image.yml/badge.svg" alt="CI Status">
</a>
<a href="https://crowdin.com/project/homarr_labs">
<img title="Translations" src="https://badges.crowdin.net/homarr_labs/localized.svg" />
</a>
<a href="https://discord.gg/aCsmEV5RgA">
  <img title="Discord" src="https://discordapp.com/api/guilds/972958686051962910/widget.png?style=shield">
</a>
</p>

<!-- Links -->
<p align="center">
  <a href="https://demo.homarr.dev/">
    <strong>Demo ✨</strong>
  </a>
  •
  <a href="https://homarr.dev/docs/category/installation-1/">
    <strong>Install 💻</strong>
  </a> •
  <a href="https://crowdin.com/project/homarr_labs">
    <strong>Translations 🈺</strong>
  </a> •
  <a href="https://discord.com/invite/aCsmEV5RgA">
    <strong>Discord 👋</strong>
  </a>
</p>


[![Features Section](./section-features.png)](https://homarr.dev/)

- 🖌️ Highly customizable with an extensive drag and drop grid system
- ✨ Integrates seamlessly with your favorite self-hosted applications
- 📌 Easy and fast app management - no YAML involved
- 👤 Detailed and easy to use user management with permissions and groups
- 👥 Support for single sign on via OIDC / LDAP
- 🙊 Safe encryption using BCrypt and AES-256-CBC for your valuable data
- 🕔 Realtime widget updates using WebSockets, tRPC and Redis
- 🔍 Search through thousands of data points in supported integrations or your data in Homarr using the fast built-in search
- 🦞 Icon picker with over 11K icons
- 🚀 Compatible with any major consumer hardware (x86, Raspberry Pi, old laptops, ...) and most OS (Windows, Linux, TrueNAS, Unraid)
- 🖥️ Extensive Kubernetes support with Helm for efficient scaling & high reliability

<br/>
<br/>

[![Widgets & Integrations Section](./section-widgets-and-integrations.png)](https://homarr.dev/docs/category/widgets)

Homarr has a [built-in collection of widgets and integrations](https://homarr.dev/docs/category/integrations), that connect to your applications and enable you to control them directly from the dashboard.

- 📥 **Torrent clients**
    - [Deluge](https://homarr.dev/docs/integrations/torrent#deluge)
    - [Transmission](https://homarr.dev/docs/integrations/torrent#transmission)
    - [qBittorent](https://homarr.dev/docs/integrations/torrent#qbittorrent-integration)
- 📥 **Usenet clients**
    - [SABnzbd](https://homarr.dev/docs/integrations/usenet#sabnzbd)
    - [NZBGet](https://homarr.dev/docs/integrations/usenet#nzbget)
- 📺 **Media servers**
    - [Plex](https://homarr.dev/docs/integrations/media-server/#plex)
    - [Jellyfin](https://homarr.dev/docs/integrations/media-server#jellyfin-and-emby)
- 📚 **Media collection managers**
    - [Sonarr](https://homarr.dev/docs/integrations/servarr#sonarr)
    - [Radarr](https://homarr.dev/docs/integrations/servarr#radarr)
    - [Lidarr](https://homarr.dev/docs/integrations/servarr#lidarr)
    - [Readarr](https://homarr.dev/docs/integrations/servarr#readarr)
- 🎞️ **Media request managers**
    - [Overseerr](https://homarr.dev/docs/integrations/media-requester)
    - [Jellyseerr](https://homarr.dev/docs/integrations/media-requester)
- 🚫 **DNS ad-blockers**
    - [Pihole](https://homarr.dev/docs/integrations/dns#pihole)
    - [AdGuard Home](https://homarr.dev/docs/integrations/dns#adguard-home)
- 🖥️ **Monitoring**
    - [Dash.](https://homarr.dev/docs/integrations/hardware)
    - [OpenMediaVault.](https://homarr.dev/docs/integrations/hardware/#openmediavault)
    - [Proxmox.](https://homarr.dev/docs/integrations/hardware/#proxmox)
- 🐳 **Container management**:
    - [Docker](https://homarr.dev/docs/integrations/containers)

<br/>
<br/>

<p dir="auto"><a href="https://demo.homarr.dev/" rel="nofollow"><img src="https://raw.githubusercontent.com/ajnart/homarr/dev/docs/section-preview.png" alt="Preview Section" style="max-width: 100%;"></a></p>
<details open="" class="details-reset border rounded-2">
  <summary class="px-3 py-2">
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-device-camera-video">
    <path d="M16 3.75v8.5a.75.75 0 0 1-1.136.643L11 10.575v.675A1.75 1.75 0 0 1 9.25 13h-7.5A1.75 1.75 0 0 1 0 11.25v-6.5C0 3.784.784 3 1.75 3h7.5c.966 0 1.75.784 1.75 1.75v.675l3.864-2.318A.75.75 0 0 1 16 3.75Zm-6.5 1a.25.25 0 0 0-.25-.25h-7.5a.25.25 0 0 0-.25.25v6.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-6.5ZM11 8.825l3.5 2.1v-5.85l-3.5 2.1Z"></path>
</svg>
    <span aria-label="Video description Untitled.video.-.Made.with.Clipchamp.mp4" class="m-1">Untitled.video.-.Made.with.Clipchamp.mp4</span>
    <span class="dropdown-caret"></span>
  </summary>

  <video src="https://private-user-images.githubusercontent.com/30572287/217098893-5880e7de-13d0-42c5-b505-f7921593396f.mp4?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTM0NDA5MTgsIm5iZiI6MTc1MzQ0MDYxOCwicGF0aCI6Ii8zMDU3MjI4Ny8yMTcwOTg4OTMtNTg4MGU3ZGUtMTNkMC00MmM1LWI1MDUtZjc5MjE1OTMzOTZmLm1wND9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA3MjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNzI1VDEwNTAxOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTY2ZWU1OGM0MTc1ZjVjOTk3NmI1MzIyZjcwMjU0ZmY4ZTNkZGJiYTJhMGZlZjk3YWI5YWMxODMwOTRiYWMwZGEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.wslHgv3JI3W9wWg3QWkJCUIWQQROj3wmqmFLHXT3KN8" data-canonical-src="https://private-user-images.githubusercontent.com/30572287/217098893-5880e7de-13d0-42c5-b505-f7921593396f.mp4?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTM0NDA5MTgsIm5iZiI6MTc1MzQ0MDYxOCwicGF0aCI6Ii8zMDU3MjI4Ny8yMTcwOTg4OTMtNTg4MGU3ZGUtMTNkMC00MmM1LWI1MDUtZjc5MjE1OTMzOTZmLm1wND9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA3MjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNzI1VDEwNTAxOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTY2ZWU1OGM0MTc1ZjVjOTk3NmI1MzIyZjcwMjU0ZmY4ZTNkZGJiYTJhMGZlZjk3YWI5YWMxODMwOTRiYWMwZGEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.wslHgv3JI3W9wWg3QWkJCUIWQQROj3wmqmFLHXT3KN8" controls="controls" muted="muted" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px; min-height: 200px">

  </video>
</details>
<br>
<br>

[![Installation Section](./section-installation.png)](https://homarr.dev/docs/category/installation-1)

Since we are updating Homarr very frequently, we recommend reading our official installation guides:

<h2>
<a href="https://homarr.dev/docs/category/installation-1/">
  Please click here for official installation instructions
</a>
</h2>

<br/>
<br/>

[![Contribute Section](./section-contribute.png)](https://opencollective.com/homarr)

<br/>

Homarr is a free to use open source project that is maintained by volunteers and developers from all over the world. We publish under the ``Apache License 2.0`` license which allows commercial usage. We invest multiple hours daily in to providing support, developing Homarr, integrating to third party software and more. We also pay for licensing and server hosting fees.
Please consider to help us cover these costs to enable the future development of Homarr. Thank you!

<h2>
<a href="https://opencollective.com/homarr">
  Please click here to sponsor us at OpenCollective
</a>
</h2>

You can also support us by helping with [translating the entire project](https://homarr.dev/docs/community/translations) to as many languages as possible or contributing directly to the code or documentation. Please read our [Contribution Guidelines](/CONTRIBUTING.md). All contributions, regardless of their size or scope, are welcome and highly appreciated! Thank you ❤️

## Sponsors
Thanks to your generous sponsors we can continue to build Homarr. Check them out for high quality and easy to use development tools.
Feel free to contact us at homarr-labs@proton.me if you wish to become a sponsor.

[![Covered by Argos Visual Testing](https://argos-ci.com/badge-large.svg)](https://argos-ci.com?utm_source=%5Bhomarr%5D&utm_campaign=oss) \
[![Supported by PikaPods](https://www.pikapods.com/static/run-button.svg)](https://www.pikapods.com/pods?run=homarr-v1)

