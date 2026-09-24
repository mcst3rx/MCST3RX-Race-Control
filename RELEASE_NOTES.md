# MCST3RX Race Control v1.1.0

Windows x64 dual-game release: **NASCAR 25 — 19 supported options; NASCAR 26 — 16 supported options.** The exact packaged executable passed user live acceptance.

## What's new

- NASCAR 25 Edit RD Points, preserving the accepted 19-option implementation.
- NASCAR 26 support for 16 options listed below, with per-game hotkeys and game selection.
- Corrected Fuel lifecycle and Ghost Mode handling.
- Aligned status controls and section headers, clean editor guidance, and layout checks at 100%, 150% and 200% DPI.

## NASCAR 25 — 19 options

| Option | Hotkey |
|---|---|
| Edit Money | NUM 0 |
| Edit Work Points | NUM 1 |
| Edit REP Points | NUM 2 |
| Edit RD Points | NUM 3 |
| Unlimited Fuel | NUM 4 |
| Max Aero Condition | NUM 5 |
| Max Engine Condition | NUM 6 |
| Max Radiator Condition | NUM 7 |
| Max Tire Condition | NUM 8 |
| Optimal Oil / Water Temp | NUM 9 |
| Edit Tire Temperature | NUM * |
| Edit Grip Rate | NUM + |
| Increase Lap Time (10 sec) | NUM - |
| Decrease Lap Time (10 sec) | NUM . |
| Easy AI | NUM / |
| Super Acceleration | DEL |
| Super Brakes | INS |
| Super Jump | END |
| Edit Laps | HOME |

## NASCAR 26 — 16 options

| Option | Hotkey |
|---|---|
| Edit Money | NUM 0 |
| Edit Work Points | NUM 1 |
| Edit REP Points | NUM 2 |
| Edit RD Points | NUM 3 |
| Unlimited Fuel | NUM 4 |
| Max Aero Condition | NUM 5 |
| Max Engine Condition | NUM 6 |
| Max Radiator Condition | NUM 7 |
| Max Tire Condition | NUM 8 |
| Optimal Oil / Water Temp | NUM 9 |
| Edit Tire Temperature | NUM * |
| Edit Grip Rate | NUM + |
| Ghost Mode | NUM - |
| Increase Lap Time (10 sec) | NUM . |
| Decrease Lap Time (10 sec) | NUM / |
| Edit Laps | PGUP |

NASCAR 26 Easy AI, Super Acceleration, Super Brakes and Super Jump are **not included**. Their NASCAR 25 counterparts remain supported. This release does not claim NASCAR 26 20/20.

## Usage and limits

Extract the complete Windows x64 ZIP and keep its executable and runtime DLLs together. Start the chosen game normally, select it in Race Control, then Connect. Use offline sessions. Disable features and use Disconnect / restore before switching games or exiting. Vehicle-dependent features may wait in menus until a valid car/session exists. Game updates may require compatibility changes.

Currency/progression edits may persist in saves; Disconnect does not undo them. Ghost OFF stops further maintenance; game behavior determines when its effect clears. If cleanup reports an error, preserve the session log and stop rather than repeatedly retrying actions.

## Verification

2,257 compiled/native/UI and audit checks passed, zero failed. The user subsequently accepted the exact executable after live testing: NASCAR 25 19 options and NASCAR 26 16 options. This acceptance does not assert compatibility with every future game build.

Executable SHA-256: `192c673ea2123ca26a967f51adb944f39f08c99560696d7cd464eb19f2e16478`.

Product version: 1.1.0. Windows file version: 1.1.0.1 (the accepted UI-corrected build). No recompilation or binary modification for publication.

The download contains no private source, recovery dumps, reference trainer, databases or experimental diagnostics. Verify the archive using SHA256SUMS.txt and extracted files using PACKAGE_SHA256SUMS.txt. License.md applies. Independent community project; not endorsed by NASCAR or the game developers/publishers.
