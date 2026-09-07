# Amoha Group, landing page preview (v3)

Live preview: https://jatin-dhir.github.io/amoha-preview/
Previous version for comparison: https://jatin-dhir.github.io/amoha-preview/v2/
Design boards (v2 direction): https://jatin-dhir.github.io/amoha-preview/design/

A motion prototype of the Amoha Group landing page, built as a single page with GSAP, ScrollTrigger, Lenis smooth scroll and
Three.js. The idea: from a line on paper to a hundred and seventy acres. The hero holds the client's own pencil sketch of the
Amoha Leaf gateway inside a semicircular arch; scrolling draws it into the finished render (a 40-frame sequence taken from the
client's video) while the arch opens across the screen. Below it: giant numerals that land one by one, the company's slogans
written across the screen over the Sanskrit word for clarity, a horizontal world of four projects with cursor-driven image
distortion, and a through-the-arch transition into the Amoha Leaf project page.

## Run locally

```bash
python -m http.server 4173
```

Then open http://localhost:4173/ (the page needs a server because of the frame files and fonts).

## Structure

- `index.html`, `frames/`, `img/`: the v3 prototype (built from the modular source in the working project by `build.mjs`)
- `v2/index.html`: the previous, quieter version (everything inline)
- `design/`: static renders of the v2 design boards

## Dependencies at runtime

Google Fonts (Bodoni Moda, Cinzel, Plus Jakarta Sans, Tiro Devanagari Sanskrit), GSAP 3.13 and Three.js 0.158 from cdnjs,
Lenis 1.1.18 from jsDelivr. No build step is needed to view the page.

## Notes

Photographs, renders and the sketch sequence come from the client's existing sites and video and are placeholders until final
assets arrive. Facts in [brackets] are unconfirmed. Not for indexing (noindex).
