# ClipForge-AI

AI-powered creative studio for turning scripts into professional videos.

## Overview

ClipForge AI Studio is a modern script-to-video generation website concept. It lets users paste a script, choose AI voice-over settings, match music and sound effects, edit scenes, preview a generated video, save projects to a gallery, and download a 1080p export package.

This build is a responsive frontend prototype created with HTML, CSS, and JavaScript. The AI generation, voice-over, subtitle, autosave, and HD export flows are simulated in the browser so the product experience can be demonstrated without a backend.

## Features

- Script to video workflow with instant scene generation
- Natural AI voice-over options for male and female voices
- English, Hindi, and Hindi + English language modes
- Mood-based music and sound effect matching
- Custom audio upload control
- Video preview with subtitles, scene badges, and no-watermark status
- Editing panel for trim, filters, transitions, subtitles, and logo layer
- Scene selector and multi-track timeline
- 1080p download mock export
- Auto-save style gallery
- Unlimited free positioning with no credits, no premium plans, and no watermarks
- Mobile and desktop responsive interface

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Local PNG preview assets

## Project Structure

```text
outputs/
  index.html
  README.md
  assets/
    scene-startup.png
    scene-education.png
    scene-health.png
    scene-news.png
```

## How to Run

Open `index.html` in any modern browser.

No build step, server, package installation, or API key is required for the current static prototype.

## Future Backend Ideas

- Connect script parsing to a real LLM
- Generate voice-over using a text-to-speech API
- Add real subtitle timing and SRT/VTT export
- Render videos with FFmpeg or a cloud rendering service
- Store gallery projects in a database
- Add authentication only if needed while keeping the free unlimited experience

## License

Free to use and customize.
