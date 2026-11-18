# PicToDraw

**Turn any photo into a step-by-step drawing guide.**

Upload or photograph anything — a person, a pet, an object, a place — and PicToDraw builds a drawing lesson from the picture itself, using the same stages art teachers use. It runs **entirely in the visitor's browser**: no uploads, no accounts, no tracking.

## The five stages

1. **See the big shapes** — the photo reduced to a blocky, squint-at-it version, so beginners block in the main masses first.
2. **Map it with a grid** — the classic grid method: a labelled grid (A, B, C… × 1, 2, 3…) over the photo, adjustable from 4–12 squares across, to copy square by square onto a matching grid on paper.
3. **Draw the outline** — a real edge-detected line map (Sobel) of the photo with an adjustable detail slider; printable for tracing, or used as a contour map.
4. **Add light & shadow** — a value study: the photo posterised into 3–5 grey tones, shaded darkest-first.
5. **Finish with details** — the photo with the outline faintly overlaid, plus finishing checks (mirror/flip trick, area-by-area comparison).

## Guide styles

- **Beginner** — plain language, grid-method-first instructions.
- **Artist** — the same stages written in proportions/block-in/value language.

Every stage is downloadable as a PNG for printing. A programmatically drawn sample cat is loaded by default so the page works the moment it opens.

## Tutorial sheet

A dedicated section redraws **all five stages as black outlines on plain white** — shapes as outlines, the grid map in black on white, the outline, the shadow-region boundaries (over a faint silhouette, so shapes survive where a tone matches the background), and the final line drawing — stacked into one tall, titled, printable sheet with a single download button, like a page from a drawing-tutorial book.

## Honest note (also stated on the page)

PicToDraw builds the guide from the picture using classic drawing *techniques* — grid transfer, edge detection, value posterisation. It does not "understand" the photo like a human teacher; the method is the same whichever photo you give it, which is exactly why it works for any subject.

## Live

Published with GitHub Pages from this repo's `gh-pages` branch (the `site/` folder).
