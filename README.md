# windows95-CSS

A small static HTML/CSS experiment that recreates a Windows 95-style desktop interface in the browser.

## Overview

This project renders a retro desktop scene with:

- desktop icons
- overlapping windows
- a taskbar with a Start button
- custom bitmap assets and a pixel-style font

There is no build step or framework setup. Everything is served directly from static files.

## Project Structure

- `index.html` - main page markup
- `css/style.css` - custom Windows 95-inspired styling
- `css/bootstrap/` - bundled Bootstrap CSS files
- `js/bootstrap/` - bundled Bootstrap JavaScript files
- `images/` - icons and window/taskbar assets
- `css/fonts/` - bundled font files

## Running Locally

Because this is a static site, you can open `index.html` directly in a browser.

If you prefer using a local server, run one from the project root. For example:

```sh
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Customization

The easiest places to start editing are:

- `index.html` for window titles, icon labels, and layout content
- `css/style.css` for colors, borders, spacing, and window positioning
- `images/` for replacing interface graphics

## Notes

- The current demo uses placeholder images from `picsum.photos` for some icons.
- Bootstrap assets are included in the repository, but the main look and feel comes from the custom stylesheet.
