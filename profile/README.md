# StarLance

StarLance is a community balance mod for StarCraft II with a ranked ladder
outside the game client. Every result comes from a replay the app uploads.

## The app

[**starlance-app**](https://github.com/SC2-StarLance/starlance-app) is the
desktop companion. It watches your StarCraft II replay folders, uploads each
new StarLance game, and keeps the queue and match state one click away. It
ships for Windows, Linux, and macOS, installs per user, and updates itself
from signed releases.

Get it from the [latest release](https://github.com/SC2-StarLance/starlance-app/releases/latest).
Windows: `sc2-replay-uploader-windows-amd64.exe`. Linux:
`sc2-replay-uploader-linux-amd64.zip`. macOS: the `starlance-uploader-macos-app`
zip for your chip; right-click the app and choose Open once.

## Behind the scenes

- [**starlance-assets**](https://github.com/SC2-StarLance/starlance-assets):
  the Blizzard artwork the app shows, pinned by commit and fetched at build
  time. Blizzard owns that art, not us.
- The app's source is MIT licensed. The StarLance name and logo are not part
  of that license.

StarCraft and StarCraft II are trademarks of Blizzard Entertainment, Inc.
This project is unofficial and not affiliated with or endorsed by Blizzard.
