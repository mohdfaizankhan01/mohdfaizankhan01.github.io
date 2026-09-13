# Portfolio

My personal site. One HTML file, no build step, no dependencies.

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 4321
```

## Layout

```
index.html     markup, styles and script
assets/        images
```

## Notes

Scroll work is IntersectionObserver plus CSS scroll-driven animations, with
static fallbacks where `animation-timeline` is missing. The timeline spine and
the canvas pieces stop rendering when they scroll out of view. Everything is
gated behind `prefers-reduced-motion`, and the page still reads with JavaScript
turned off.

Type is Poppins, Playfair Display and Mrs Saint Delafield, loaded from Google
Fonts. The signature in the contact section is Mrs Saint Delafield converted to
outlines ahead of time so nothing has to be parsed at runtime.
