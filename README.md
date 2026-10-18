# Hollow Suns — The Broken Orbit

Early playable voxel space-adventure prototype.

**[Download Mac and Windows builds](https://github.com/leoscarnes/hollow-suns-playtest/releases/latest)**

This repository distributes playable builds and instructions. Game source is not included.

## Install

- **Mac (Apple Silicon):** open the DMG, drag Hollow Suns into Applications, then launch it. This playtest is unsigned and not notarized. If macOS blocks it, review the download and use System Settings → Privacy & Security → Open Anyway if you trust it. Intel Macs are not supported by this package.
- **Windows (64-bit):** extract the entire ZIP and launch Hollow Suns.exe. Keep the Data folder and DLLs beside the executable. No Unity installation is required. The executable is unsigned.

## Controls

WASD moves on foot; mouse looks; Space jumps; Shift sprints. E/right-click opens nearby furniture. V changes the character view.

Ship: E/F beside a flightworthy hull boards. W/S adjusts throttle, mouse steers, Space/C rises/descends, Shift boosts. E assists landing near clear ground. V switches cockpit/chase. F walks the cabin or retakes the helm, including in space. N opens navigation; 1–4 selects a destination in space. **X cancels autopilot/approach and returns manual control.**

## LAN building sandbox

Both players use the same release on the same trusted local network. Land first, then Esc → Multiplayer. One player selects Host; the other selects Join and enters the host computer's local IPv4 address. Allow the game on private networks if Windows Firewall asks. Port: TCP 28460.

LAN currently supports exploration, shared mining/building and shared supplies in a separate persistent co-op save. Combat, crafting, furniture inventories, ships, planet travel and story progression are disabled in LAN. Those remain solo features. This is not an authenticated Internet server; do not expose the port publicly.

## Prototype limitations

The moon boss remains the original placeholder encounter; the large lunar-base prototype is not yet integrated. Ship combat, damage/repair, ownership registries and salvage yards are unfinished. Visuals and performance are still in development.

Native Mac regression and two-instance LAN tests are automated. Windows builds compile successfully, but execution on a physical Windows PC and actual Mac–Windows networking remain unverified. Please report OS, release version, reproduction steps and screenshots in Issues; do not post private saves or personal data.

## Credits

Sound effects by Kenney: Impact Sounds, Sci-fi Sounds and Interface Sounds, CC0. License files are bundled with the downloads.
