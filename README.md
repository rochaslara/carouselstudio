# Carrossel

A browser-based editor for animated image carousels. Pick a template, choose which images to show, style the background, and export a looping GIF or MP4.

Everything runs locally in the browser. Images are never uploaded anywhere.

## Use it

Open `index.html` in Chrome, Edge or Safari. No build step or server is needed.

To host it, enable GitHub Pages on this repository (Settings → Pages → deploy from the `main` branch, root folder).

## Features

- **52 templates** in five groups: 3D & Perspective, Carousel, Stack, Zoom & Reveal, and Grid. Cards are drawn in real 3D with WebGL2.
- **Images:** add, drop or paste images. Click to show or hide each one, and drag to reorder.
- **Cards:** ratio, size, corner radius, spacing, shadow and outline.
- **Motion:** time per card, easing, pause between steps, tilt and reverse.
- **Background:** on or off, solid, gradient, glow or your own image (with blur and darken), plus grain.
- **Export:**
  - MP4 up to 4K at 24, 30 or 60 fps, with optional loop repeats.
  - GIF up to 1080 px, transparent when the background is off.

Your project, images included, is saved in your browser so it's still there when you reopen the page.

## Notes

- MP4 export is fastest in browsers with WebCodecs (Chrome, Edge, recent Safari). Others record in real time and may produce WebM.
- MP4 has no transparency, so a disabled background renders as black in video.
