# Warframe Market Intelligence

A stunning, real-time market tracker for Warframe Prime Sets. It utilizes the `api.warframe.market` endpoints to fetch the latest prices, averages, and trade volumes for various categories (Warframes, Primary, Secondary, Melee, Sentinels).

## Features
- **Dynamic Caching**: LocalStorage caches initial values and updates live in the background without blocking UI rendering.
- **Glassmorphic UI**: High-end modern UI utilizing Google web fonts, custom gradients, and CSS Backdrop filters.
- **Sort & Search**: Easily find what you want and sort by Price, Volume, or Name.

## Getting Started
Due to modern web browser CORS (Cross-Origin Resource Sharing) policies, simply opening the HTML file via `file://...` may cause proxy blocking issues or performance throttling.

To run this properly as a mini-project:

1. **Option 1: Python Server (Recommended)**
   If you have Python installed, you can start a local development server by running the included `serve.py` script from the terminal.
   ```bash
   python serve.py
   ```
   This will host the file correctly at `http://localhost:8000`, and you can open `http://localhost:8000/prime_market_researcher.html` in your browser.

2. **Option 2: Use VS Code Live Server**
   If you use Visual Studio Code, install the "Live Server" extension, right click `prime_market_researcher.html` and click "Open with Live Server".

## Adjustments
You can easily jump into `prime_market_researcher.html` to adjust the `API_V2` settings or change color palettes inside the `:root` pseudo-class in the `<style>` block.