# ssalimuto — Movie Studio

A lightweight, browser-based photo-to-movie creator with Uganda-inspired branding. Add a photo, position it, choose a gentle motion style, add a title, preview the six-second scene, and export a WebM video.

## Run it

Open `index.html` in a recent browser, or serve this folder with any static web server. No build step, dependencies, or account required.

## Photo privacy and face preservation

Photos are loaded locally in your browser; the app does not upload them to a server. Motion is applied to the **whole original image layer** using canvas drawing and position/scale transforms. It does not use generative AI, face replacement, or face regeneration. This keeps the original faces and image content intact while the picture moves as a single layer. It does not independently animate a person inside the photo.

The current export creates a six-second WebM file (video only, no audio). Browser support for recording canvas video is required; try a recent Chrome or Firefox if export is unavailable.

## Features

- Local photo upload (JPG, PNG, WEBP; up to 20 MB)
- Drag-to-position preview and directional adjustment controls
- Still, gentle drift, slow zoom, and pan motion presets
- Adjustable photo scale and optional title overlay
- Six-second preview timeline and WebM export
- Responsive editor layout
