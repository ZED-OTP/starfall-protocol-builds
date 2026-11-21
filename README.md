# Starfall Protocol (playtest builds)

A 2D survivors-like roguelite with loot-driven buildcrafting, for Windows and macOS. Move and dash through an
ever-growing swarm while your weapons fire on their own; every level-up and every decrypted item reshapes the build. Survive 15 minutes, beat the
Conductor and extract with your Cipher Caches.

This is an early playtest build. Feedback is very welcome.

## Download

Get the latest build from **[Releases](../../releases/latest)**:

**Windows** (10/11, 64-bit): download `StarfallProtocol-windows.zip`, unzip it anywhere and run `StarfallProtocol.exe`.
The game is not code-signed, so Windows SmartScreen may warn you: click **More info → Run anyway**.

**macOS** (11 Big Sur or newer; Apple Silicon M1/M2/M3/M4 and Intel): download `StarfallProtocol-macos.zip`, unzip it
and move `Starfall Protocol.app` to Applications. The app isn't registered with Apple, so the first launch is blocked:
1. Double-click the app and close the warning ("Apple could not verify…").
2. Open **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to Starfall Protocol.
3. Confirm with **Open** (and your password if asked). After that it opens normally.

Your save is stored in `%APPDATA%\Godot\app_userdata\Starfall Protocol\` (Windows) or
`~/Library/Application Support/Godot/app_userdata/Starfall Protocol/` (macOS).

## Controls

| Action | Keyboard / mouse | Controller |
|---|---|---|
| Move | WASD / arrow keys | Left stick |
| Dash | Space | A |
| Siege Dome (when charged) | E | Y |
| Pick a level-up card | 1 / 2 / 3 or click | D-pad + A |
| Reroll / Banish / Skip | Q / B / Tab | X / Y / LB |
| Pause, settings | Esc | Back |
| Return to the hub (run end) | R | Start |
| Lock an item (hub) | L | Y |

Weapons, grenade and melee fire automatically.

## Reporting a bug or crash

The game writes a log of every session. After a bug or crash, open this folder. On Windows, paste it into the Explorer
address bar:

```
%APPDATA%\Godot\app_userdata\Starfall Protocol\logs
```

On macOS, in Finder choose **Go → Go to Folder…** and paste:

```
~/Library/Application Support/Godot/app_userdata/Starfall Protocol/logs
```

`godot.log` is the latest session, and the timestamped files are older ones (the 10 newest are kept). Attach the log of
the session with the problem to an [issue](../../issues), with a line on what you were doing. The log holds the
build version, your OS, CPU and graphics card, each run's map seed, level-up picks and how the run ended, plus any
errors. A crash report can also show the folder the game runs from, which may include your user name.

## Feedback

Open an [issue](../../issues) or tell me directly. Most useful: what confused you in the first minute, why you died,
and whether you wanted another run.

## Credits

Made with [Godot Engine](https://godotengine.org) 4.7 (MIT, see `licenses/Godot-LICENSE.txt`). Font: Space Grotesk, SIL Open Font License 1.1
(see `licenses/`).
