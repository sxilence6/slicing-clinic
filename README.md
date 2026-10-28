# slicing clinic

## download

- **mac** (apple silicon + intel): [slicing-clinic-mac.dmg](https://github.com/sxilence6/slicing-clinic/releases/latest/download/slicing-clinic-mac.dmg)
- **windows** (64-bit): [slicing-clinic-windows.zip](https://github.com/sxilence6/slicing-clinic/releases/latest/download/slicing-clinic-windows.zip)

These always point to the newest version. Older ones are under [releases](https://github.com/sxilence6/slicing-clinic/releases).

## opening it the first time

The app isn't signed by Apple or Microsoft, so both systems complain once.

**mac:** drag "slicing clinic" onto Applications and open it. macOS says it can't check it for malware: click "Done", then open System Settings → Privacy & Security, scroll down, click "Open Anyway" next to "slicing clinic" and confirm with your password.

**windows:** right-click the zip → "Extract All...", don't run it from inside the zip. Open the folder, double-click `slicing clinic.exe`. On "Windows protected your PC" click "More info" → "Run anyway". Keep the whole folder together.

## using it

Drop an audio file on the window (wav, aif, mp3…), slice it, shape the slices in design, smash them together in layer, export. Long tracks first ask which part to slice.

---

The Windows build includes [FFmpeg](https://ffmpeg.org) 9.0.2 (GPL, [gyan.dev](https://www.gyan.dev/ffmpeg/builds/) essentials build, source: [FFmpeg 9.0.2](https://github.com/FFmpeg/FFmpeg/tree/n9.0.2)) so mp3/flac/m4a open. Its license is in the app folder.
