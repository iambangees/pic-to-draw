# PicToDraw

**Turn any photo into a simple step-by-step drawing tutorial.**

Upload or photograph anything — a person, a pet, an object, a place — and PicToDraw turns it into a basic 3-step drawing tutorial in black outline on plain white, like a page from a tutorial book. It runs **entirely in the visitor's browser**: no uploads, no accounts, no tracking.

## The three steps

1. **Start with basic shapes** — the photo reduced to its biggest blocky shapes, drawn as an outline: copy the circles, ovals, triangles and rectangles first.
2. **Sketch the outline** — only the main lines of the picture (a higher edge threshold keeps it to the big contours), drawn lightly over the shapes.
3. **Finish the drawing** — the full outline with all the detail, ready to copy carefully and darken.

Each step is a black-on-white line drawing (Sobel edge detection) with a short, plain instruction and its own PNG download. A **tutorial sheet** stacks all three steps onto one titled white page with a single download button, for printing.

A programmatically drawn sample cat is loaded by default so the page works the moment it opens.

## Design note

An earlier version had five stages (grid method, value/shading study, sliders, beginner/artist modes). Abubakar — the product's owner — asked for it simpler: *"just basic stuff"*, like the cat tutorial. So the grid, the shading stage, the sliders and the modes were removed. The three-step outline progression is the whole product now.

## Live

Published with GitHub Pages from this repo's `gh-pages` branch (the `site/` folder).
