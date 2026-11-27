# Webtools · experimentation

Research tools for an immersive audiovisual piece. Everything runs in the browser.

## Tools

- **Spectral travel** (`tools_spectre_000/`): the spectrogram of a sound becomes a 3D space. Time is depth, and the camera moves forward as the sound plays. Each frequency becomes particles that light up, close in and burst with the sound.
  - Space play/pause · ←/→ seek 5 s · H hide panels · P export PNG · R record WebM (with sound)
  - Drop any sound file on the image to analyse it.

## Run locally

Browsers block reading the default sound from `file://`. Two options:
- open `index.html` with a local server (e.g. VS Code Live Server);
- or open the page directly and drop the sound file on the image.

The shared interface lives in `ui/` (`ui_001.css`, `ui_001.js`) and the fonts in `fonts/`.
