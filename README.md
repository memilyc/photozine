# 📖 Photozine

> Turn your photos into a printable mini-magazine! 

**Photozine** is a lightweight, mobile-friendly single-page web application designed to help creators format an 8-page pocket zine from a single sheet of A4 paper. It automatically handles the complex page layout, sequencing, and orientation flips required for traditional physical zine folding.

Live Demo: `https://<your-username>.github.io/<your-repo-name>/`

---

## ✨ Features

* **Smart Bulk Upload:** Upload up to 8 photos simultaneously. The app instantly sequences them across pages 1 to 8, skipping slots that already have images.
* **Intuitive Frame Adjustments:** Tap/click and drag to adjust the position of your images. Fine-tune your framing using the integrated zoom (`+` / `-`) control panel.
* **Zero-Gap Printing Grid:** Layout boxes sit edge-to-edge seamlessly to maximize printable space on a physical sheet of A4 paper.
* **Automatic Fold Orientation:** Images placed in the top row (Pages 7, 6, 5, 4) are rotated 180° automatically, ensuring they appear right-side up once printed, cut, and folded.
* **Smart Canvas Interactions:** Dragging coordinates dynamically invert when interacting with top-row frames, keeping touch gestures intuitive.
* **Guiding Markers:** Displays a dashed cutting line right beneath pages 6 and 5 with an indicator scissor emoji (`✂`).
* **High-Resolution Export:** Download your completed layout instantly in **PNG**, **JPG**, or a print-ready **A4 Landscape PDF**.
* **Modern Aesthetics & Dark Mode:** Built with a GitHub-inspired sleek ecosystem featuring a clean light mode and dark mode theme toggle.

---

## ✂️ Zine Assembly Guide

1. **Print:** Export your design as a PDF and print it out in **A4 Landscape** mode. Ensure "Fit to page" or "Actual size" is selected depending on your printer's border margins.
2. **The Horizontal Fold:** Fold the paper in half lengthwise (hot dog style), crease it, and open it back up.
3. **The Vertical Folds:** Fold the paper in half crosswise (hamburger style), then fold the outer edges into the center crease to make 8 distinct panel sections. Open it back up.
4. **The Cut:** Fold the paper in half crosswise again. Cut along the red dotted line (between Pages 6/5 and Pages 1/2) starting from the folded center spine outward. Do **not** cut all the way to the edges.
5. **The Assembly:** Open the sheet fully. Fold it lengthwise along your original horizontal crease. Push the two ends inward together—the center slit will open up into a diamond shape. Keep pushing until the pages form a cross booklet shape, then flatten them to finalize your 8-page mini magazine!

---

## 🛠️ Built With

* [Tailwind CSS](https://tailwindcss.com/) - Modern utility-first layout styling.
* [Alpine.js](https://alpinejs.dev/) - Super lightweight, reactive frontend state control.
* [html2canvas](https://html2canvas.hertzen.com/) - High-definition image element capturing.
* [jsPDF](https://rawgit.com/MrRio/jsPDF/master/docs/index.html) - Seamless client-side PDF document generation.

---

## 📈 Changelog

### v1.1.0 (Current)
* **Rebranding:** Transformed the general grid sequencer tool into **Photozine**, a dedicated pocket mini-magazine creator.
* **Dark Mode Added:** Introduced an automated/manual theme toggle adapting GitHub-styled core color tokens (`#0d1117`, `#161b22`, `#21262d`).
* **Bulk Upload Engine:** Programmed multi-file select handling to automatically map inputs sequentially to Pages 1–8.
* **Zine Layout Optimization:** Removed canvas grid gaps entirely to ensure full print utilization. Added a 180-degree rotation engine for top row pages (7, 6, 5, 4).
* **UX Adjustments:** Programmed inverted dragging matrices specifically for upside-down frames so touch tracking handles intuitively. Added an overlay cutting guideline below pages 6 and 5.

### v1.0.0
* Initial release of the 4x2 A4 landscape grid tool.
* Implemented manual single-image upload slots matching a strict 4:5 portrait frame aspect ratio.
* Added core touch/drag configuration mechanics and standard PNG/JPG/PDF generation features.

---

## 📄 License

This project is licensed under the **MIT License**—completely free to use, modify, distribute, or host for personal and commercial purposes.

```text
MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.