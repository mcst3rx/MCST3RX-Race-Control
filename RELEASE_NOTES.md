# MCST3RX Race Control v1.0.0

**Supported game:** NASCAR 25

**Platform:** Windows x64

**Executable:** `MCST3RX-Race-Control.exe`

**NASCAR 26:** Future / not yet supported

## Overview

The initial public release includes 18 gameplay options, 18 hotkeys, six live
value editors, a native racing-themed interface, Connect / Disconnect restore
controls, feature audio feedback, Mute and Global Hotkeys controls, and community
links for YouTube, Ko-fi, Discord and GitHub.

## Download and run

1. Download `MCST3RX-Race-Control.exe` and `SHA256SUMS.txt` from the
   [official v1.0.0 release](https://github.com/mcst3rx/MCST3RX-Race-Control/releases/tag/v1.0.0).
2. Keep both files together and verify the checksum below before running.
3. Start NASCAR 25 normally, then launch `MCST3RX-Race-Control.exe`.
4. Select **Connect** and check GAME STATUS before enabling a feature.
5. Use the feature button or its displayed hotkey. For an editor, enter a value
   first. Use a period for decimals and no commas.
6. Use **Mute** to suppress feature feedback sounds. Use **Global Hotkeys** to
   control hotkey registration.

## Restore and close

Disable active features when finished, then use **Disconnect / restore** before
closing the application or game. Check any reported status or error. Turning a
feature off is not a substitute for the full Disconnect / restore workflow.
If restoration reports an error, stop using features and close the game normally
before starting a fresh session. Changes to saved progression may persist;
Disconnect / restore is not a save-game rollback.

## Compatibility and limitations

- NASCAR 25 is the supported game. NASCAR 26 is not yet supported.
- Compatibility with every game build, future update or Windows configuration
  is not guaranteed. Report the game version when reporting a problem.
- Online/private-lobby compatibility is not guaranteed by this release. Do not
  infer multiplayer compatibility from offline results or interface screenshots.
- Use only in environments where modification is permitted. This release does
  not authorize interference with other players or game services.
- This is a Windows x64 application; other platforms are not supported.

## Verify the download

In PowerShell, from the folder containing the downloaded executable, run:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath .\MCST3RX-Race-Control.exe
```

Compare the complete hash with the entry for `MCST3RX-Race-Control.exe` in
`SHA256SUMS.txt` (letter case does not matter). Do not run the download if the
hash differs; download it again from the official release.

## Support and license

See the [project README](https://github.com/mcst3rx/MCST3RX-Race-Control/blob/main/README.md)
for official community links and the
[issue chooser](https://github.com/mcst3rx/MCST3RX-Race-Control/issues/new/choose)
for bug reports and feature requests.

This is proprietary software distributed under the
[MCST3RX Race Control license](https://github.com/mcst3rx/MCST3RX-Race-Control/blob/main/License.md).
MCST3RX Race Control is an independent community-made project and is not
associated with or endorsed by NASCAR or the game's developers or publishers.
Third-party names and trademarks belong to their respective owners. The software
is provided as is; see the license for the full terms.
