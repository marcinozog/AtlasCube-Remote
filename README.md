# AtlasCube Remote

An Android app to control an **AtlasCube** internet‑radio device over your local
network. It gives you full remote control of playback, playlists, sound,
Bluetooth, scheduled events and the device's settings — all from your phone.

## What it does

- **Radio control** — play/stop, next/previous, volume, and a programmable
  keypad, with live "now playing" info (station, title, codec, bitrate). Keypad
  buttons are configured with a command picker plus a "raw" mode for advanced
  combinations.
- **Playlist** — browse the device playlist, mark **favorites** (pinned to the
  top), reorder, edit and save back to the device.
- **Equalizer** — 10‑band EQ that mirrors the device sound.
- **Bluetooth** — switch the device audio source between Radio and Bluetooth,
  see track metadata and drive transport (prev/play/pause/next) and volume.
- **Events** — create and manage the device's scheduled events (reminders,
  birthdays, name days, anniversaries and radio alarms). These run on the device
  itself, so they fire even when your phone is off.
- **Discovery** — scan the local network for AtlasCube devices automatically.
  Tap a result to add it, pre‑filled with its name and address; devices you've
  already saved are flagged and tap through to edit.
- **Device Settings** — a hub mirroring the device's settings page: Display,
  Audio, WiFi, NTP, Sleep & Wake, Theme (with a colour‑palette editor), MQTT,
  Screensaver, and Tools/OTA (firmware update).

## Screenshots

<!-- Replace the placeholders below with real screenshots once captured. -->

| Keypad | Playlist | Bluetooth |
| :----: | :------: | :-------: |
| ![Keypad](docs/screenshots/keypad.png) | ![Playlist](docs/screenshots/playlist.png) | ![Bluetooth](docs/screenshots/bluetooth.png) |

| Equalizer | Events | Settings |
| :-------: | :----: | :------: |
| ![Equalizer](docs/screenshots/equalizer.png) | ![Events](docs/screenshots/events.png) | ![Settings](docs/screenshots/settings.png) |

## Navigation

The bottom bar has five tabs — **Devices, Keypad, Playlist, Bluetooth, More** —
which can be switched by tapping or by **swiping left/right**. Detail screens
(device settings, events, equalizer, MQTT widgets, etc.) open full‑screen from
the **More** tab; system back returns to the tabs.

## Works offline

Settings and events screens stay usable when the device is offline: they show
the last values fetched while online with an "Offline" banner, in read‑only
mode. Saving re‑enables once the device is reachable again.

## Getting started

1. Make sure your phone and the AtlasCube device are on the same Wi‑Fi network.
2. On the **Devices** screen, add the device by its IP address or hostname
   (e.g. `192.168.1.150`) — or let the automatic network scan find it and tap to
   add.
3. Open it and you're in control.
