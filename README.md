# Co-op Explorers

A playable Godot prototype for web browsers and Android.

- [Play in your browser](https://ddreamer94.github.io/co-op-explorers/)
- [Download the Android APK](https://github.com/DDreamer94/co-op-explorers/releases/download/mobile-controls-2026-10-15/co-op-explorers.apk)

## Play

Choose **Solo + AI** and start to play immediately without a server. The prototype includes the Mountain Observatory encounter and 20 earlier traversal experiments. It currently uses a third-person camera; first-person play and the deeper puzzle redesign are pending.

Mobile: play in landscape. Touch lower-left open space to place the floating joystick, then drag to walk/run. Use the spaced round buttons on the right for Jump, Interact/Load/Fire, Crouch, sling setup, Stack AI and Reset. Pinch open world space to zoom; moving/action fingers keep their own controls. The web client displays a rotation prompt in a narrow portrait window.

The top-left panel now shows a compact personal task. Tap **i** for team/role details and help. Corrective feedback stays visible separately; a loaded passenger sees the automatic-release countdown. The quest minimap remains top-right.

Desktop: WASD/arrows move, Shift runs, Space jumps, E interacts, F sets up/packs the sling, C crouches, T controls the AI tower, R returns to the start, Escape opens the menu.

## Multiplayer

GitHub Pages hosts the web client only. Online rooms require a separately running Co-op Explorers WebSocket server. This preview uses the owner's private Tailscale server, so every player must have access to that tailnet and the server must be running.

In the web menu, replace the **Co-op server** address with your server's `wss://HOST:8072` address. The default derived GitHub hostname is not a multiplayer backend. Choose **Humans only** or **Humans + AI**, create a room, and share the server address and room code with friends. The APK retains the existing preview server configuration. Public matchmaking and ordinary LAN discovery are not included.

## Android

This is an ARM64 APK signed with the development key, intended for direct prototype testing. Download it on your Android phone, open the file, and allow installation from that browser or file manager if Android requests it. It is not a Play Store release. It has been installed and launched on an Android emulator; physical-phone testing is still pending.

## Build provenance

Updated 2026-10-15 with the mobile control and overview camera improvements. Map layouts, puzzle mechanics and AI planners are unchanged; the deeper cooperative puzzle redesign remains pending. The checksums in `build-manifest.json` identify the hosted files and release APK.

This repository contains deployment files; the development project and private working evidence remain in the local project.

## Engine notices

Made with [Godot Engine](https://godotengine.org/), distributed under its [MIT license](https://godotengine.org/license/). Engine and bundled third-party license notices are included in [GODOT_NOTICES.txt](GODOT_NOTICES.txt).
