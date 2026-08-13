# AI-audio-visualizer

AI-audio-visualizer is a browser-based audio visualizer that lets you play local audio files and watch them react in real time.

It runs entirely in the browser, so there's no account or backend required.

## Features

- Real-time audio visualizer
- Multiple visualization styles
- Different themes
- Audio queue / playlist
- Shuffle and loop
- Volume and playback controls
- 3-band EQ
- EQ presets
- Bass boost, smoothing and glow controls
- Compact / expanded UI
- Fullscreen mode
- Microphone input
- System / tab audio input
- Visualization recording
- Drag and drop audio files
- Local preference saving
- PWA / offline support

## Live

https://hongyuekai427-bit.github.io/AI-audio-visualizer/

## How it works

AI-audio-visualizer uses the browser's Web Audio API to analyze the audio and draw the visualization on a canvas.

Files selected from your computer are handled locally by the browser. Microphone and system-audio modes use the browser's normal permission prompts.

There is no AI-audio-visualizer backend.

## Running it locally

Clone the repository:

```bash
git clone https://github.com/hongyuekai427-bit/AI-audio-visualizer.git
