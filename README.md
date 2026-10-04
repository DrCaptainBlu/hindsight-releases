# Hindsight releases

Windows builds of **Hindsight** -- always-on replay-buffer capture (GPU screen
grab + up to four separate audio tracks) and a multi-track clip editor in one
app.

This repo only holds release builds. Hindsight checks the latest release here
when it opens (and from Settings -> Updates -> Check for Updates), and updates
itself in place.

Each release attaches `Hindsight.exe`. A first-time install also needs the
`ffmpeg` folder (`ffmpeg.exe` + `ffprobe.exe`) next to the exe; updates only
replace the exe.
