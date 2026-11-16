# HandScript

> ### Launch HandScript Directly (iPhone, Android & Laptop)
>
> **Once GitHub Pages is enabled (see 1-minute setup below), tap your live link below to open HandScript immediately—no downloads or terminal needed:**
>
> **[Launch HandScript App](https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/)**  
> *(Tap the pencil **Edit** icon on this `README.md` in GitHub and replace `YOUR_GITHUB_USERNAME` and `YOUR_REPO_NAME` with yours—or tap the live link GitHub automatically adds in the **Deployments** / **About** section of your repository.)*

---

## One-Time Setup on GitHub (No Terminal Required)

You can set this up completely from your browser or phone:

1. Open your repository on **github.com** → go to **Settings** → **Pages** (in the left sidebar).
2. Under **Build and deployment → Source**, choose **GitHub Actions**.
3. Go to the **Actions** tab → select **Deploy HandScript to GitHub Pages** → tap **Run workflow** *(or it runs automatically on every sync/push to `main`/`master`)*.
4. In ~1 minute, GitHub publishes your live app at:
   `https://<your-username>.github.io/<your-repo-name>/`

---

## Use Like a Mobile / Desktop App (No App Store Needed)

- **iPhone / iPad (Safari):** Open your GitHub Pages link → tap the **Share** button → **Add to Home Screen**. HandScript opens full-screen directly from your Home Screen.
- **Android (Chrome):** Open your GitHub Pages link → tap **⋮ Menu** → **Add to Home screen / Install app**.
- **Mac / Windows (Safari, Chrome, Edge):** Open the link → click **Install** in the address bar (or **File → Add to Dock** in Mac Safari).

---

## Features

- **14 bundled handwriting fonts** stored locally in `public/fonts` + **Upload my handwriting font** (`.ttf`, `.otf`, `.woff`, `.woff2`) saved in IndexedDB + **Joined mode** for cursive scripts
- **Formulas (`Σ Formula`)**: simple syntax (`a/b`, `x^2`, `sqrt(x)`, `int_0^pi`) and LaTeX (`$...$` inline & `$$...$$` centered display), rendered as wobbly handwritten strokes snapped to ruled lines
- **Tables (`Table`)**: hand-drawn wobbly grids with corner overshoot, Excel/Sheets paste, column width ratios, and multi-page row splitting
- **Images & Diagrams**: **Image** insertion with **Sketchify** edge-drawing filter + interactive **`rough.js` Diagram** editor with handwritten labels
- **Document Import & OCR**: `.txt`, `.docx`, and `.pdf` import (with optional scanned-PDF OCR), drag-and-drop, and clipboard paste
- **Notebook Headers & Page Numbers**: handwritten `Name`, `Roll no.`, `Subject`, `Date`, draggable header position, and customizable bottom-corner page numbers
- **Real Notebook Paper & Calibration**: neutral white ruled/blank paper or upload custom JPG/PNG/WebP/HEIC/PDF pages with auto-detected ruled lines, straighten/crop/lighting tools, and draggable guides
- **Phone Photo Output Look**: `Clean scan`, `Phone photo`, `Dim room photo`, and `Notebook flat-lay` simulation presets
- **Multi-Doc, Bulk Mode & Export**: auto-saved documents, JSON backup export/import, Bulk ZIP batch conversion, high-resolution PNG/JPG, and multi-page PDF export
