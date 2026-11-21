# Anything Launcher

A fast, modpack-first Minecraft launcher built for the **Create Anything SMP** community server. One Discord link installs the entire mod pack and keeps it in sync — no manual downloads, ever.

## Install

1. Download `AnythingLauncher-Setup-x.y.z.exe` from the [latest release](https://github.com/Tim-CrA/anything-launcher-dist/releases/latest).
2. Run the installer.
3. Open the install link posted in Discord — the launcher creates the build, presets the server and downloads the whole mod pack.

That's it. The launcher updates itself: it checks GitHub Releases every few hours, and a banner appears when a new version is ready — one click downloads and installs it silently.

## What it does

- **Server packs that install themselves** — the mods folder is brought to an exact match with the server's manifest on every launch; only the difference is downloaded, verified by SHA-1
- **Full Minecraft support** — every version, automatic Java runtimes, Fabric / Quilt / NeoForge / Forge
- **Mod catalog** — Modrinth and CurseForge, batch installs, version pinning, red-highlighted incompatible mods
- **Skins** — pixel editor, 3D preview, gallery, one command applies your skin server-side
- **Friends & presence** — friend codes, LAN and internet rooms, join a friend's world in one click
- **Crash recovery** — a dedicated window names the culprit mod and offers a minimal fix
- **Discord sign-in** — one click, the app is built into the installer

## Links

- Server: `create-anything.myddns.me`
- Install link (pinned in Discord): `anything-launcher://install?manifest=https%3A%2F%2Fraw.githubusercontent.com%2Fcreateanythingsmp%2Fcra-mods-pack%2Fmain%2Fmods-manifest.json&name=Create%20SMP&server=create-anything.myddns.me%3A25565`

This repository holds releases only; the source lives in the private `anythink-launcher` repository.
