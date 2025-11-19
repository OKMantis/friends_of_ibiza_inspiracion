# Friends of Ibiza Inspiración

A static landing page built with Bootstrap 4 to showcase inspirational content for Friends of Ibiza. The page includes subscription prompts, featured content cards, and supporting imagery tailored for English and Spanish audiences.

## Project structure
- `index.html`: Main entry point that loads Bootstrap, Font Awesome, and the page markup.
- `stylesheets/style.css`: Global stylesheet imported by the page, which also pulls in component styles.
- `stylesheets/components/card.css`: Styles for the featured content card layout.
- `images/`: Asset folder for logos and photography used throughout the layout.
- `fonts/`: Custom font assets referenced by the styles.

## Getting started
1. Clone this repository.
2. Open `index.html` directly in your browser, or serve the directory with a simple server:
   ```bash
   python -m http.server 8000
   ```
3. Navigate to `http://localhost:8000` to preview the site.

## Development tips
- Update layout and content in `index.html`. The page relies on Bootstrap 4.3.1, jQuery 3.3.1, and Popper.js via CDN links defined at the bottom of the file.
- Adjust global styling in `stylesheets/style.css` and card presentation in `stylesheets/components/card.css`.
- Add or replace visual assets in the `images/` directory and update references in `index.html` accordingly.
