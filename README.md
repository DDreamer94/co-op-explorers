# Co-op Explorers

A Godot cooperative puzzle prototype for browsers and native Android.

- [Play in your browser](https://ddreamer94.github.io/co-op-explorers/)
- [Download the Android APK](https://github.com/DDreamer94/co-op-explorers/releases/download/lobby-beta-2026-10-15/co-op-explorers.apk)

## Play together

Choose **Online multiplayer**, create a room and share **Copy invite** or its
six-digit code. Friends can browse available rooms or use **Join code**. Each
person controls one explorer. The host chooses **AI fill** separately; new human
rooms default to humans only. Mountain Observatory supports 2–4 participants.

Testers do not need Tailscale. The beta server runs on the owner's Mac through
a temporary Cloudflare public tunnel. The Mac and server must stay online;
this is beta hosting with no uptime guarantee. Both clients fetch the current
public address from this site's `server.json`. Under **Server settings**, **Use
public server** clears an intentionally saved custom address.

**Play with AI** runs locally without multiplayer hosting. **Nearby multiplayer**
in the Android app can host a room and scan the same Wi-Fi/hotspot; keep the
hosting app open. Browser players should use Online with an invite/code, even
on the same Wi-Fi; that path needs internet. Physical-phone Wi-Fi discovery still
needs validation. Bluetooth and offline browser LAN play are not included.

## Controls

Mobile: landscape. Touch lower-left open space to place the floating joystick,
then drag to walk/run. Round right buttons handle Jump, Interact/Load/Fire,
Crouch, sling setup, Stack AI and Reset. Pinch open world space to zoom. The
quest minimap is top-right; tap **i** for team/role details. The phone lobby uses
one pane and a separate encounter chooser, with Start/Leave visible in room views.

Desktop: WASD/arrows move, Shift runs, Space jumps, E interacts, F sets up/packs
the sling, C crouches, T controls the AI tower, R returns to the start, Escape
opens the menu.

## Prototype scope

Mountain Observatory is one cooperative mechanics encounter. Twenty earlier
traversal experiments remain available. Deeper puzzles and first-person play
are pending; this build retains its third-person camera. This update adds
lobbies/public access and improves their mobile layout; puzzle mechanics and
AI planners are unchanged.

The ARM64 APK is development-signed for direct beta testing. Download it on an
Android phone, open the file and allow installation from your browser/file
manager if Android requests it. This is not a Play Store release. Emulator
crossplay and in-app hosting were tested; physical-phone performance remains
unverified.

## Build provenance

Release `lobby-beta-2026-10-15`. `build-manifest.json` identifies the exact hosted
files and APK. This repository contains deployment files; the development
project and private working evidence remain local.

## Engine notices

Made with [Godot Engine](https://godotengine.org/) under its
[MIT license](https://godotengine.org/license/). Engine and bundled third-party
notices are included in [GODOT_NOTICES.txt](GODOT_NOTICES.txt).
