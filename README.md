# Snowtils

> **Disclaimer:** This mod automates in-game actions which may be against Hypixel's rules. Use at your own risk. I am not responsible for any bans or penalties.

A client-side Hypixel Skyblock utility mod for Fabric. All features are toggleable via keybinds (under **Options → Controls → Snowtils**) or the in-game `/snowtils` command.

## Modules

### auto_accept (Default: `H`)
Automatically clicks the first bracketed `[text]` dialogue option in NPC chat messages. Adds a 350ms delay before clicking.

### spirit_mask_hud (Default: `J`)
Shows a countdown timer under the crosshair when your Spirit Mask procs. Shows "Spirit: Ready" when available.

### lock_rotation (Default: `K`, default: OFF)
Straight up blocks mouse movement from reaching the camera.

### left_click_etherwarp (Default: none, default: OFF)
Replaces left-click attacks with the etherwarp key sequence when holding an Aspect of the Void or Aspect of the End.

## Commands

All commands are prefixed with `/snowtils`.

- `/snowtils list` — Lists all modules with their ON/OFF status and current keybinds
- `/snowtils toggle <module>` — Toggles a module on or off
- `/snowtils bind <module> <key>` — Changes the keybind for a module (e.g. `h`, `f5`, `numpad0`, `mouse2`)

### Examples

```
/snowtils bind auto_accept f5
/snowtils bind spirit_mask_hud k
/snowtils toggle auto_accept
```

You can also toggle modules with their default keybinds (`H` for auto-accept, `J` for Spirit Mask HUD) or by rebinding them in **Options → Controls → Snowtils**.
