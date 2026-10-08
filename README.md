# AI DJ

A gesture-controlled music player. Raise and lower your hands in front of the webcam to DJ the track live: your right wrist sets the playback speed and your left wrist sets the volume.

**[Live demo →](https://ayanprakash35.github.io/dj-man/)**

## Features

- Real-time wrist tracking with **PoseNet**
- Right wrist height maps to 0.5x–2.5x playback speed
- Left wrist height maps to volume

## How to play

1. Allow camera access and step back so both wrists are in view.
2. Press **Play**.
3. Move your **right** wrist up and down to change speed, and your **left** wrist to change volume.

## Built with

[p5.js](https://p5js.org/) + p5.sound, [ml5.js](https://ml5js.org/) PoseNet

## Run it locally

The webcam needs a page served over `http://localhost` (not opened as a file):

```bash
git clone https://github.com/Ayanprakash35/dj-man.git
cd dj-man
python3 -m http.server 8000
```

Then open <http://localhost:8000> and allow camera access.

Everything runs in the browser. No video leaves your machine.
