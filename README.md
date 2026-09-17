# ChuRan (Olivia) Ma &mdash; Portfolio Website

A personal portfolio showcasing architectural design, urban infill research, parametric façades, and visual art installations by ChuRan (Olivia) Ma.

---

## 🌟 Highlights & Features

1. **Wix Project 3 Minimalist Aesthetic**:
   - Palette inspired by [Natalia's Artwork Project 3](https://natalia071019.wixsite.com/artwork/project3): `#e7dee1` blush-grey hero band, `#e7dee1` footer, crisp borders (`#eae6e7`).
   - Typography: Google Fonts `Aboreto` (curatorial display) and `Inter` (editorial body).
   - Fixed Wix navigation bar with interactive dropdown menu and brand icon.

2. **VIEW MY WORKS (4 Curated Project Cards)**:
   - **Project 01**: *Spatial Flow & Tectonic Envelope* (Architectural Design & Modal Gallery)
   - **Project 02**: *Urban Infill & Porous Thresholds* (Urban Architecture & Modal Gallery)
   - **Project 03**: *Kinetic Assemblies & Filter* (Parametric Façade & Modal Gallery)
   - **Project 04**: *The Blurred Boundary: Care, Protection and Control* (Visual Art, Archival Installation & 34-Page Storyboard Layout)

3. **Project 04 Dedicated Exhibition (`exhibition.html`)**:
   - Complete 34-page visual art storyboard layout mapped from original design archives.
   - **Zero Horizontal Scrollbars**: Sticky sub-nav with far-right arrow controls (`‹` and `›`).
   - **White Background Composite**: Seamlessly integrated Page 01 primary timetable artwork.
   - **Camera-Locked 3-Phase Sequence (Pages 24–26)**: Interactive click-to-switch continuum (Composure → Resistance → Containment) plus Triptych side-by-side view.
   - **High-Resolution Lightbox Modal**: Multi-image navigation with keyboard controls (`Left`/`Right`/`Escape`).
   - **Authentic Storyboard Spreads Drawer**: Complete 34-page 1:1 scan gallery.

4. **Client-Side Security (CMS Admin)**:
   - Built-in administrative dashboard in `index.html`.
   - Salted SHA-256 Web Crypto API hash validation (zero plaintext passwords stored).

---

## 🚀 How to Deploy on GitHub Pages

1. **Create a GitHub Repository**:
   - Create a new public (or private) repository on GitHub (e.g. `churan-portfolio` or `<your-username>.github.io`).
2. **Push this `web/` folder**:
   ```bash
   cd web
   git init
   git add .
   git commit -m "Initial release of ChuRan Ma portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
3. **Enable GitHub Pages**:
   - Go to your repository **Settings** &rarr; **Pages**.
   - Under **Build and deployment**:
     - **Source**: `Deploy from a branch`
     - **Branch**: `main` / folder: `/ (root)`
   - Click **Save**.
   - In 1–2 minutes, your website will be live at:
     `https://<your-username>.github.io/<your-repo-name>/` (or your custom domain).

---

## 📁 Repository File Structure

```text
├── index.html            # Portfolio homepage (4 work cards, About Me, Contact, CMS)
├── exhibition.html       # Project 04: The Blurred Boundary (34-page storyboard)
├── me.jpg                # Artist portrait
├── .nojekyll             # Prevents GitHub Pages Jekyll build overrides
├── .gitignore            # Git exclusion rules
├── README.md             # Project documentation & deployment guide
└── assets/               # Production image assets
    ├── arch/             # Architectural project previews (arch1, arch2, arch3)
    ├── wix/              # Wix hero background watermark
    └── hongdoudou/       # 34 original scans & 40 extracted high-res images
        ├── page_01.jpg .. page_34.jpg
        └── extracted/
            ├── p01_img1_6.png (pure white background composite)
            └── ...
```

---

&copy; 2026 ChuRan (Olivia) Ma. All rights reserved.
