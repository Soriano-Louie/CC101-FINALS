# CC101-FINALS

# CC101-FINALS — Interactive Solar System Explorer

Project: A client-side interactive Solar System explorer built with standard web technologies. It presents planet information pages, textured visuals, and a simple server-side backend for feedback/storage.

What it is
- Interactive educational website showcasing planets and moons with image textures, info pages, and a navigable UI.
- Lightweight frontend with optional PHP endpoints for feedback and basic data persistence.

Resume-friendly summary
- Built a responsive, interactive Solar System explorer using HTML5, CSS3 and vanilla JavaScript; implemented modular planet info pages and media assets.
- Integrated PHP endpoints (`menuFiles/db.php`, `menuFiles/feedback.php`) for form submission and basic server-side handling.

Key features
- Dedicated info pages for planets and moon with images and textures.
- Responsive layout and menu system (multi-frame/fragment architecture present in `framesets/`).
- Simple server-side scripts for storing/processing feedback.

Technologies & languages
- HTML5 — markup and semantic structure.
- CSS3 (responsive layouts, custom styles, `global.css`, `styles.css`, `menuFiles/menu.css`).
- JavaScript — client-side interactivity and content loading (`loader.js`, other scripts).
- PHP — lightweight server-side handlers (`menuFiles/db.php`, `menuFiles/feedback.php`).
- Assets: images, textures, custom fonts.

Development environment / tools
- Works in any static file web server or by opening `index.html` in a browser for full frontend experience.
- For server-side features enable a PHP-capable server (XAMPP, WAMP, LAMP) and configure a database if persistence is required.

How to run (quick)
1. Open [index.html](index.html) in a modern browser for the static frontend.
2. To enable feedback/db functionality, host the project on a PHP-enabled server and ensure write permissions for storage or configure a MySQL database and update `menuFiles/db.php` accordingly.

Suggested resume bullets (pick and edit to match your role)
- Developed an interactive Solar System web application using HTML5, CSS3 and JavaScript; created modular planet info pages and optimized media assets for web delivery.
- Implemented PHP-based form handling and lightweight persistence endpoints to capture user feedback.
- Managed project assets (textures, fonts, images) and structured the site for maintainability across `framesets/`, `planet-infos/`, and `menuFiles/`.

Repository layout (high level)
- `index.html`, `home.html`, `explore.html` — primary pages.
- `planet-infos/` — per-planet information pages.
- `menuFiles/` — navigation, PHP endpoints and auxiliary pages.
- `imgs/`, `textures/`, `fonts/` — media assets.
