# tada-design-lab
Ta-Da Design Lab is the collaborative work of stylist Tamera Holland and technician Danielle Ackerman. Together they blend intuition and precision to create tactile, intelligent design. The duo is also developing The Universal Fashion Framework — a system for understanding style itself. Vibe-coded and hand-made in Oregon, USA.
# ✨ TaDa Design Lab  
**Curated. Minimal. Intelligent. Crafted. Playful.**

A micro-studio web presence and product gallery built for design in motion.  
This repo powers the public site for **Ta-Da Design Lab**, hosted on **GitHub Pages**.

---

## 🧭 Overview
**Goal:**  
Showcase limited-run textile pieces and design experiments with an editorial, tactile sensibility — part atelier, part digital showroom.

**Stack:**  
- Static HTML / CSS / JS (no frameworks, no dependencies)  
- Hosted on GitHub Pages  
- Designed for ultra-light performance and full visual control  

---

## 🌐 Live Site  
**URL:**  
[https://danielleackerman.github.io/tada-design-lab](https://danielleackerman.github.io/tada-design-lab)  
*(replace `yourusername` with your actual GitHub handle)*

Once you push to `main`, Pages auto-deploys within ~1 minute.

---

## 🗂 Folder Structure

    tada-design-lab/
    ├─ index.html          → main gallery / home page
    ├─ about.html          → about / studio philosophy
    ├─ assets/             → css, fonts, favicon, mp4 header, icons
    ├─ photos/             → curated, final, web-ready product images
    ├─ _drafts/            → raw photos, working edits, test assets
    ├─ _inspo/             → reference pulls, moodboards, concept art
    ├─ _ignore/            → temp or scratchpad files not for versioning
    └─ .gitignore          → excludes junk folders & local files

🟢 **Public files:** `index.html`, `about.html`, `assets/`, `photos/`  
🟡 **Private / local only:** folders prefixed with `_` (ignored by Git)

---

## ✏️ Workflow
1. **Work** in `_drafts/`  
   Drop test images, crops, mockups, anything in progress.  
2. **Promote** to `photos/`  
   Once finalized, move images here for live use.  
3. **Edit** in VS Code  
   Use Live Server to preview (`index.html` or any other page).  
4. **Push** to GitHub  

       git add .
       git commit -m "update images + layout"
       git push

   GitHub Pages will auto-publish to your live link.

---

## 🧩 Tech Notes
- Parallax hero section uses vanilla JS (`requestAnimationFrame`) for smooth motion across browsers.  
- Site color palette and typography set via CSS `:root` variables:

        --oat: #e7dfd2;
        --taupe: #b8aa96;
        --brass: #b9975b;
        --ink: #222;

- Fully responsive (CSS grid & flex layouts).  
- Compatible with desktop + mobile (no external libraries).  

---

## 🧵 To-Do / Future Iterations
- Add product detail pages or hover captions  
- Integrate short header video (`assets/fash_tada.mp4`)  
- Explore subtle scroll animations / reveals  
- Connect QR hangtags → product pages  

---

## 📦 Deployment
1. Go to GitHub → **Settings → Pages**  
2. **Branch:** `main`  
   **Folder:** `/ (root)`  
3. Wait 60 seconds, then visit your live URL.

---

## 🪡 Brand Philosophy
> *Ta-Da Design Lab is where material meets wit. Every object is a micro-performance — an intelligent reveal made tactile.*

---

© 2025 **Ta-Da Design Lab**  
Hand-coded & stitched in Oregon.
