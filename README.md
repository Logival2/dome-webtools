# Webtools · experimentation

Research tools for an immersive audiovisual piece. Everything runs in the browser.
Online: https://logival2.github.io/dome-webtools/ (the home page lists the versions).

## Versions

- **V1 · Spectral travel** (`tools_spectre_000/`): the spectrogram of a sound becomes a 3D space. Time is depth, and the camera moves forward as the sound plays. Each frequency becomes particles that light up, close in and burst with the sound; anomalies standing out from the background are framed and measured.
  - Opens with a short intro (place and date typed on black); `?intro=0` or `?t=42` skip it.
  - Space play/pause · ←/→ seek 5 s · H hide panel · P export PNG · R record WebM (with sound)
  - Drop any sound file on the image to analyse it (mono, stereo, 5.0, 5.1…).

## Run locally

Browsers block reading the default sound from `file://`. Two options:
- open the tool folder with a local server (e.g. VS Code Live Server);
- or open the page directly and drop the sound file on the image.

Each tool carries its own `ui/` and `fonts/`, so it opens from any server root.
