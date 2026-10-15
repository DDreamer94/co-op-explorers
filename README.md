# Co-op Explorers

A playable Godot prototype for web browsers and Android.

- [Play in your browser](https://ddreamer94.github.io/co-op-explorers/)
- [Download the Android APK](https://github.com/DDreamer94/co-op-explorers/releases/download/prototype-2026-10-15/co-op-explorers.apk)

## Play

Choose **Solo + AI** and start to play immediately without a server. The prototype includes the Mountain Observatory encounter and 20 earlier traversal experiments. It currently uses a third-person camera; first-person play and the deeper puzzle redesign are pending.

Desktop: use the controls shown in the game. Mobile: use the left joystick and right action buttons; landscape orientation is recommended.

## Multiplayer

GitHub Pages hosts the web client only. Online rooms require a separately running Co-op Explorers WebSocket server. This preview uses the owner's private Tailscale server, so every player must have access to that tailnet and the server must be running.

In the web menu, replace the **Co-op server** address with your server's `wss://HOST:8072` address. The default derived GitHub hostname is not a multiplayer backend. Choose **Humans only** or **Humans + AI**, create a room, and share the server address and room code with friends. The APK retains the existing preview server configuration. Public matchmaking and ordinary LAN discovery are not included.

## Android

This is an ARM64 APK signed with the development key, intended for direct prototype testing. Download it on your Android phone, open the file, and allow installation from that browser or file manager if Android requests it. It is not a Play Store release. It has been installed and launched on an Android emulator; physical-phone testing is still pending.

## Build provenance

Published 2026-10-15 from the existing verified local exports. No gameplay code was changed for this publication. The checksums in `build-manifest.json` identify the hosted files and release APK.

This repository contains deployment files; the development project and private working evidence remain in the local project.

## Engine notices

Made with [Godot Engine](https://godotengine.org/), distributed under its [MIT license](https://godotengine.org/license/). Engine and bundled third-party license notices are included in [GODOT_NOTICES.txt](GODOT_NOTICES.txt).
