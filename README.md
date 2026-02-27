# 亡犬 Dead Dog - Game Website

Promotional website for the Dead Dog game.

## Features

- **Responsive design** - Mobile and desktop compatible
- **Demo download section** - Download link easily updatable
- **Steam integration** - Direct link to game page
- **Atmospheric design** - Amber tones matching the game's shadow/stealth theme
- **Steam assets** - Header, capsule, and screenshot images from the Steam store page

## Updating the Demo Link

In `index.html`, find this line:

```html
<a href="#" class="btn btn-demo" id="demo-download">
```

Replace `href="#"` with your demo download URL. Example:

```html
<a href="https://example.com/dead-dog-demo.zip" class="btn btn-demo" id="demo-download">
```

## Running the Site

Open `index.html` in your browser, or use a local server:

```bash
# Python
python -m http.server 8000

# Node.js (npx)
npx serve
```

Then visit http://localhost:8000

## File Structure

```
OyunSite/
├── index.html    # Main page
├── styles.css    # Styles
├── script.js     # JavaScript
├── images/       # Steam assets (header, capsule, screenshot)
└── README.md     # This file
```
