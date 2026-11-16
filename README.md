# HandScript

An offline text-to-handwriting converter contained in a single `index.html` file (HTML, CSS, vanilla JavaScript) with a local copy of jsPDF and self-hosted fonts. No accounts, no server, and no watermarks.

## Features
- **14 bundled handwriting fonts** stored locally in `/fonts`
- **Realistic ink rendering** with `multiply` paper blending, per-character variation, subtle ink edge softness, baseline drift, and optional **Joined mode** for connected cursive scripts
- **Formatting markers**: `**bold**`, `*italic*`, `__underline__`, `- ` bullets, `1. ` numbered lists, and tab indentation
- **Neutral white & custom notebook papers**: crisp neutral white default ruled paper with double red margin, blank white paper, or upload JPG/PNG/WebP/HEIC/PDF notebook pages into IndexedDB ("My papers" with rename/delete), automatic ruled-line & margin detection, optional straighten/crop/lighting normalization, and draggable calibration guides
- **Phone photo Output Look**: presets (`Clean scan`, `Phone photo`, `Dim room photo`, `Notebook flat-lay`) with camera perspective skew, uneven lighting, shadows, vignette, glare, grain, and seeded per-page variation
- **Full-resolution export**: individual PNG/JPG pages (2480 × 3508 px A4 or 2550 × 3300 px Letter) and multi-page PDF with selectable quality (`High`, `Medium`, `Small`) and empty metadata

## How to Open Locally

Because browsers restrict loading local font files and ES modules over `file://`, serve the built folder (or project folder) with a quick one-line local web server. Once served, it works completely offline.

### macOS
1. Open **Terminal**.
2. Change into the HandScript folder (or `dist/` if built):
   ```bash
   cd /path/to/handscript
   ```
3. Start a local server using Python 3 (built into macOS) or Node.js:
   ```bash
   python3 -m http.server 3000
   ```
   *(Or if using the Vite project folder: `npm install && npm run dev`)*
4. Open Safari or Chrome and go to `http://localhost:3000`.

### Windows
1. Open **Command Prompt** or **PowerShell** inside the HandScript folder (or `dist/` if built).
2. Start a local server with Python or Node.js:
   ```powershell
   python -m http.server 3000
   ```
   *(Or with Node.js: `npx serve -l 3000` or `npm install && npm run dev`)*
3. Open Edge or Chrome and go to `http://localhost:3000`.
