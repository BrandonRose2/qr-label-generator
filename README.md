# QR Label Generator

A drag-and-drop web app for laying out QR code label PNGs onto a 4x6" print sheet (300 dpi, 1200x1800px) — sized for DYMO label printers.

## Features
- Drag & drop any number of QR PNG files
- Auto-suggests a unit name/number from each filename (editable)
- Reorder labels by dragging
- Configurable header text (e.g. property code) and grid size (3x2, 3x3, 3x4, 3x5)
- Automatically splits into multiple sheets if you add more labels than fit on one
- Download individual sheets or all at once

## Usage
Open `index.html` in any modern browser — no build step, no server required. Everything runs client-side.

You can also enable **GitHub Pages** (Settings → Pages → Deploy from branch → main / root) to host it at a public URL.
