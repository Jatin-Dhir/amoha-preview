# Amoha Group, landing page preview

Live preview: https://jatin-dhir.github.io/amoha-preview/
Alternative direction (bolder, WebGL): https://jatin-dhir.github.io/amoha-preview/v3/
Design boards (v2 direction): https://jatin-dhir.github.io/amoha-preview/design/

A motion prototype of the Amoha Group landing page, built as a single page with GSAP, ScrollTrigger and Lenis smooth scroll.
One idea: a clear opening in the dark. The page is black and the only light comes through a semicircular arch; scrolling opens the
arch until the whole screen is the land. Below it: the figures at a glance, the meaning of the name, a projects index whose arch
viewer fills with each project on hover, and a through-the-arch transition into the Amoha Leaf project page.

## Run locally

```bash
python -m http.server 4173
```

Then open http://localhost:4173/.

## Structure

- `index.html`: the prototype (everything inline: images, CSS and JavaScript)
- `v3/`: an alternative, bolder direction with a sketch-to-render hero and WebGL project worlds
- `design/`: static renders of the design boards

## Dependencies at runtime

Google Fonts (Cinzel, Cormorant Garamond, Plus Jakarta Sans, Tiro Devanagari Sanskrit), GSAP from cdnjs and Lenis from jsDelivr.
No build step is needed to view the page.

## Notes

Photographs and renders come from the client's existing sites and video and are placeholders until final
assets arrive. Facts in [brackets] are unconfirmed. Not for indexing (noindex).
