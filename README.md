# MIGU project website

Static project page based on the design of `open-world-planning.github.io`.
Content and the framework figure are adapted from the supplied MIGU manuscript.
Author names, affiliations, and the equal-contribution note are supplied by the project owner.

## Preview

Run `python3 -m http.server 8000` from this directory and visit http://localhost:8000.
No build step is required.

## Videos

Task1–Task8 use `static/assets/videos/optimized/task1.mp4` through `task8.mp4`.
Original `T1_experiment.mp4` through `T8_experiment.mp4` files are preserved.
The web copies use 1280×800 (16:10) with square pixels: the full frame is
stretched vertically relative to the original 16:9 footage, without cropping.
Encoding: H.264, CRF 23, slow preset, yuv420p, AAC 96 kb/s, fast-start MP4.
Task posters are extracted from the processed videos at one second.

The overview video is displayed above the key message in `index.html`. It uses `static/assets/videos/optimized/overview.mp4`, processed
with the same 16:10 dimensions and compression settings. The original
`static/assets/videos/overview.mp4` is preserved.
The Paper button opens `static/assets/papers/MIGU.pdf`.

Original footage and the unused placeholder are excluded from Git; compressed web copies are committed.
