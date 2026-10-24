# Keychron K2 HE — keymap

Keymap export from [Keychron Launcher](https://launcher.keychron.com) for a K2 HE (BR RGB) used on macOS.

## Layers

- **Layer 0 / 1** — Mac profile. Function row sends media/brightness keys; hold `fn` for F1–F12.
- **Layer 2 / 3** — Windows profile (untouched defaults).

## Customizations

| Key | Keycode | Behaviour |
| --- | --- | --- |
| Right Shift (Layer 0) | `0x3252` = `RSFT_T(KC_UP)` | Tap → `↑`, hold → Right Shift |

Settings that live outside this file (set in the Launcher):

- HE Mode → Actuation distance: **2.0 mm** on every key (Default profile).
- HE Mode → One Key Multiple Commands: none bound. The old "Right Shift / Up" macro binding left Shift held on the host; the mod-tap keycode replaces it.

## Restore

Keychron Launcher → connect the keyboard → **Keymap** → **Import** → pick `keymap.json`.
