# Keychron K2 HE — keymap

Keymap export from [Keychron Launcher](https://launcher.keychron.com) for a K2 HE (BR RGB) used on macOS.

## Layers

- **Layer 0 / 1** — Mac profile. Function row sends media/brightness keys; hold `fn` for F1–F12.
- **Layer 2 / 3** — Windows profile (untouched defaults).

## Customizations

| Key | Keycode | Behaviour |
| --- | --- | --- |
| Right Shift (Layer 0) | `0x3252` = `RSFT_T(KC_UP)` | Tap → `↑`, hold → Right Shift |

## Files

| File | Launcher section | Contents |
| --- | --- | --- |
| `keymap.json` | Keymap → Export | 4 layers of keycodes |
| `he-profile-default.json` | HE Mode → Default profile → ⋯ → Export | Actuation distance **0.4 mm** on every key, no One Key Multiple Commands bound, no Rapid Trigger |

The old "Right Shift / Up" macro binding (One Key Multiple Commands) left Shift held on the host; the mod-tap keycode replaces it.

## Restore

Keychron Launcher → connect the keyboard →

1. **Keymap** → **Import** → `keymap.json`
2. **HE Mode** → **Default** profile → ⋯ → **Import** → `he-profile-default.json`
