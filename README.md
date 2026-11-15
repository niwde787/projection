# Projection

A browser-based projection mapping tool. One HTML file, no install, runs on WebGL2.

**Live:** open `index.html` from GitHub Pages, drag the window onto your projector, press `F` for fullscreen and `H` to hide the controls.

## Features
- **Corner pin** warping with perspective for flat surfaces
- **Mesh warp** (1×1 to 8×8 grid) for curved or uneven surfaces
- **Masks**: cut-outs or show-only-inside shapes, with feathering
- **Edge blending & crop**: soft edges, gamma, and a one-click 2-projector split
- **Sources**: test grid, solid, gradient, scan bars, pulse, edge chase, rings, audio spectrum, your own image/video, or a copy of another surface
- **Shapes**: 20 surface shapes: rectangle, square, rounded rect/square, circle, ellipse, triangle, rounded triangle, diamond, trapezoid, parallelogram, pentagon, hexagon, octagon, star, rounded star, 6-point star, hexagram, cross, drop, with adjustable edge softness
- **Touch-friendly UI**: bottom tab bar (Layers, Content, Shape, Warp, Show, Room, Setup) with pop-up sheets; pinch to zoom and two-finger pan, mouse-wheel/trackpad zoom, zoom bar with Fit
- **Rotate** surfaces and masks: drag the ↻ handle (snaps to 45°, Shift = 15° steps), type an angle, ±90°, Level, or `[` `]` keys
- **Grid & snap**: alignment grid, snap to grid, snap corners/edges between surfaces and masks, snap to output edges, project the grid for lining up the projector (hold Alt to disable snap)
- **Dimensions & canvas size**: enter a surface's real width × height to get its aspect ratio, projector pixels and the canvas size to design content at; estimate the other surfaces from one measurement; export blank template PNGs with a real-world grid
- **Reference photo**: plan the layout on a photo of your space
- **Preview mode**: simulates how the projection will look in a dark room
- **Audio reactive**: surfaces pulse to bass / mid / high from an audio file
- **Cues**: record looks and crossfade between them with Space
- **Output window**: clean projector output in a second window
- **Projects**: save any number of named projects in the browser (with thumbnails) including their videos, images, music and room photo; autosave; open, duplicate, delete; export/import a single `.pmap` project file to move between devices

## Keys
| Key | Action |
|---|---|
| `1`–`4` | select corner |
| Arrows (+Shift) | nudge 1px (10px) |
| `M` | toggle mesh warp |
| `G` | toggle grid |
| `[` `]` (+Shift) | rotate 1° (15°) |
| `+` / `-` / `0` | zoom in / out / fit |
| `Alt` (hold) | drag without snapping |
| `N` / `Del` | new / delete surface |
| `Tab` | next surface |
| `P` | preview |
| `H` | output mode |
| `O` | output window |
| `F` | fullscreen |
| `B` | blackout |
| `Space` | GO next cue |
| `S` / `Ctrl`+`S` | save project (`Ctrl`+`Shift`+`S` = save as copy) |

## Demo
[Living room test](media/living-room-mapping-test.mp4)
