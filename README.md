# Malaika Flipbook

An interactive flipbook viewer — browse through pages with a realistic 3D page-turn animation.

**Live:** [https://malaika.vercel.app](https://malaika.vercel.app)

## Features

- **3D flipbook animation** — realistic page-turn with CSS 3D transforms
- **Book & Slider modes** — switch between spread view and single-page slider
- **Click, drag & swipe** — navigate pages with arrows, keyboard, touch swipe, or thumbnail strip
- **Dark mode** — toggle between light and dark themes
- **Page-turn sounds** — different pitch for forward/back, ambient room tone option
- **Fullscreen** — go immersive with fullscreen viewing
- **Responsive** — works on desktop, tablet, and mobile

## Tech

Single HTML file — no build step, no dependencies. Uses CSS 3D transforms for animation and Web Audio API for sound.

## Development

No build step needed. Open `public/baby_brother_flipbook.html` in a browser.

To serve locally:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000`

## Deploy to Vercel

1. Push to GitHub
2. Import project in Vercel — served as a static site automatically
