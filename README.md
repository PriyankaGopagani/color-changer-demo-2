# Color Changer

## Overview
A lightweight, single-file web app to explore colors. Click to generate a random color, or type your own hex code. The app now prominently displays the current color’s hex code on screen, updating live as the color changes.

## Setup
- No build tools or dependencies required.
- Open index.html in any modern browser.

## Usage
- Generate a random color:
  - Click anywhere on the large color area, or
  - Press the Random button, or
  - Press the Space key.
- Enter a specific color:
  - Type a hex code (supports #RRGGBB or #RGB, with or without #) and press Enter or click Apply.
- Copy the current color code:
  - Click Copy code or press Ctrl/Cmd+C.
- Share/link a color:
  - The URL hash updates to the current hex (e.g., #34D399). Share the link to open directly to that color.

The hex code is always visible in large text over the color and automatically switches to black or white for best contrast.

## Improvements in Round 2
- Added on-screen display of the current hex color code that updates in real time as the color changes.
- Improved readability with automatic contrast-aware text color and subtle shadow.
- Quality-of-life additions: copy-to-clipboard, URL hash sharing, and persistence of the last color across sessions.