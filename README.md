# 📖 Photozine

> Turn your photos into a printable mini-magazine! 

**Photozine** is a lightweight, mobile-friendly single-page web application designed to help creators format an 8-page pocket zine from a single sheet of A4 paper. It automatically handles the complex page layout, sequencing, and orientation flips required for traditional physical zine folding.

Live Demo: `https://memilyc.github.io/photozine/`

---

## ✨ Features

* **Smart Bulk Upload:** Upload up to 8 photos simultaneously. The app instantly sequences them across pages 1 to 8, skipping slots that already have images.
* **Granular Fluid Framing:** Click/touch and drag to freely pan your *uncompressed original photos* within the layout boxes. Fine-tune your layout configurations using the integrated scale (`+` / `-`) control panel.
* **Per-Slot Removals:** Easily delete an uploaded photo from any single frame to swap or adjust it independently without clearing your whole canvas.
* **Maximized Space Edge-to-Edge Grid:** Layout boxes sit completely edge-to-edge with **zero margins, zero padding, and zero gaps** to utilize 100% of your physical sheet of paper.
* **Automatic Fold Orientation:** Images placed in the top row (Pages 7, 6, 5, 4) are rotated 180° automatically, ensuring they appear right-side up once printed, cut, and folded.
* **Smart Canvas Interactions:** Dragging coordinates dynamically invert when interacting with top-row frames, keeping touch gestures intuitive.
* **Clean Print Export Pipeline:** 100% guideline-free digital renders. Uses a high-definition native virtual canvas running on `Blob URLs` to prevent mobile tab crashes while outputting crisp **PNG**, **JPG**, or print-ready **A4 Landscape PDF** configurations.
* **Modern Aesthetics & Dark Mode:** Built with a GitHub-inspired sleek ecosystem featuring a clean light mode and dark mode theme toggle.

---

## ✂️ Zine Assembly Guide

1. **Print:** Export your design as a PDF and print it out in **A4 Landscape** mode. **Crucial:** Select "Actual size" (100% scaling) in your printer properties to prevent the grid margins from shifting!
2. **The Horizontal Fold:** Fold the paper in half lengthwise, crease it, and open it back up.
3. **The Vertical Folds:** Fold the paper in half crosswise, then fold the outer edges into the center crease to make 8 distinct panel sections. Open it back up.
4. **The Cut:** Fold the paper in half crosswise again. Slice cleanly along the horizontal spine dividing **Page 6 and Page 5** from the bottom row frames (marked inside the application preview canvas). Do **not** cut all the way to the outer edges.
5. **The Assembly:** Open the sheet fully. Fold it lengthwise along your original horizontal crease. Push the two ends inward together—the center slit will open up into a diamond shape. Keep pushing until the pages form a cross booklet shape, then flatten them to finalize your 8-page mini magazine!

---

## 🛠️ Built With

* [Tailwind CSS](https://tailwindcss.com/) - Modern utility-first layout styling.
* [Alpine.js](https://alpinejs.dev/) - Super lightweight, reactive frontend state control.
* [jsPDF](https://rawgit.com/MrRio/jsPDF/master/docs/index.html) - Seamless client-side PDF document generation.

---

## 💡 Inspiration & Credits

* **Production Concept:** This project was heavily inspired by this amazing creative project layout on Instagram Reels. Check out the original viral walkthrough here: [Instagram Folding Guide Reel](https://www.instagram.com/reel/DZC0_i2ynTB/?).
* **Engineering:** Created with 🤍 by **Gemini** — engineered to solve uncompressed memory heap errors with custom pixel coordinate mapping structures.

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