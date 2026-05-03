# My Travel Journal

A static web project that turns personal travel memories into an interactive guessing game. Six glowing, animated houses each represent a hidden destination — visitors click into a house and try to guess where it is based on clues and photos.

## Pages

- **`index.html`** — Landing page with a floating house illustration and a call-to-action to begin the journey.
- **`journey.html`** — Grid of six animated, glowing house cards (Tokyo, Israel, Greece, London, Russia, Bangkok). Each card links to its destination page.
- **`house.html`** — Individual destination page, loaded dynamically via URL query param (`?id=tokyo`, etc.). Shows clues and lets visitors guess the location.

## Structure

```
traveljournal-static/
├── index.html
├── journey.html
├── house.html
└── images/
    ├── house1.png – house15.png   # Illustrated house assets
    ├── houses1.jpg                # Background scene
    └── notes1.png, notes2.png     # Journal note assets
```

## Running Locally

No build step needed — open `traveljournal-static/index.html` directly in a browser.

```bash
open traveljournal-static/index.html
```

## Tech

Pure HTML/CSS. No frameworks or dependencies beyond Google Fonts (Lobster, Lora).
