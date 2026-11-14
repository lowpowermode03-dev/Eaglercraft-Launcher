# EaglerCraft Launcher

A community-made, browser-based launcher interface for compatible Eaglercraft clients.

**Current launcher version: 3.1.0**

## What's new in 3.1.0

- Complete graphite-and-violet UI redesign inspired by modern desktop game launchers.
- Redesigned sidebar, dashboard, version picker, launch controls, cards and settings.
- Improved responsive behavior and keyboard focus visibility.

## What is included

- Game page with a searchable client/version selector and custom HTML launch option.
- Client library and server browser.
- Downloads catalog, mod manager and skin browser.
- Launcher settings, including supported Wisp connection options.
- Community chat page.
- Launcher Tools command center with local profiles, server bookmarks, recent launches, quick notes, diagnostics, keyboard shortcuts and JSON workspace backup/restore.
- Version favorites and a searchable Feature Hub.
- Responsive forest-green interface for desktop and mobile browsers.

## Run it

This is a static website. No build step or package installation is required.

1. Download or clone this repository.
2. Keep the folder structure intact, especially `game/`, `mods/`, `skins/` and `resources/`.
3. Serve the repository root through a static web host or local HTTP server.
4. Open `index.html` through that host.

Some browser features, client networking modes and pop-up launch modes may require HTTPS and browser permissions. Opening the page as a local `file://` URL may limit storage, networking or client launch behavior.

## Browser data

Launcher profiles, bookmarks, notes, recent launches, favorites and preferences are stored locally in the browser using local storage. They are not automatically synchronized between devices. Use the workspace backup tool to export or import supported launcher data.

The Feature Hub currently contains **210 local preference controls**. Those controls are not 210 independently implemented gameplay features; only controls connected to a working launcher utility change behavior.

## Compatibility notes

The launcher is a web interface. It does not create new Eaglercraft versions or make an incompatible client work with a server. Client availability and features depend on the client files included in the repository. Wisp support depends on the selected client and its own compatibility.

The launcher cannot bypass browser security restrictions, popup blocking, CORS, mixed-content rules or server-side access controls.

## Repository contents

- `index.html` — launcher home and game launch controls
- `script.js` — existing launcher and launch behavior
- `launcher-core.js` — launcher-wide local utilities and command center
- `styles.css` — shared interface styles
- `clients.html`, `servers.html`, `downloads.html`, `mods.html`, `skins.html`, `settings.html`, `chat.html`, `news.html` — launcher sections
- `feature-hub.html` — local preference controls and utilities

The root-level `GX-Launcher 2.0.zip` is a legacy archive and is not the 3.0.0 release package.

## Credits and notices

This is an independent, community-made project and is not an official Minecraft, Mojang or Microsoft product. Eaglercraft and third-party client components remain subject to their respective projects' licenses and terms. Keep upstream notices and attribution with the components they cover.

## Source

[GitHub repository](https://github.com/lowpowermode03-dev/Eaglercraft-Launcher)
