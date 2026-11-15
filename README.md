# Projection

A browser-based projection mapping tool. One HTML file, no install, runs on WebGL2.

**Live:** open `index.html` from GitHub Pages, drag the window onto your projector, press `F` for fullscreen and `H` to hide the controls.

## Features
- **Corner pin** warping with perspective for flat surfaces
- **Mesh warp** (1×1 to 8×8 grid) for curved or uneven surfaces
- **Masks**: cut-outs or show-only-inside shapes, with feathering
- **Edge blending & crop**: soft edges, gamma, and a one-click 2-projector split
- **Sources**: test grid, solid, gradient, scan bars, pulse, edge chase, rings, audio spectrum, your own image/video, or a copy of another surface
- **Dimensions & canvas size**: enter a surface's real width × height to get its aspect ratio, projector pixels and the canvas size to design content at; estimate the other surfaces from one measurement; export blank template PNGs with a real-world grid
- **Reference photo**: plan the layout on a photo of your space
- **Preview mode**: simulates how the projection will look in a dark room
- **Audio reactive**: surfaces pulse to bass / mid / high from an audio file
- **Cues**: record looks and crossfade between them with Space
- **Output window**: clean projector output in a second window
- Save to browser, export/import layouts as JSON

## Keys
| Key | Action |
|---|---|
| `1`–`4` | select corner |
| Arrows (+Shift) | nudge 1px (10px) |
| `M` | toggle mesh warp |
| `N` / `Del` | new / delete surface |
| `Tab` | next surface |
| `P` | preview |
| `H` | output mode |
| `O` | output window |
| `F` | fullscreen |
| `B` | blackout |
| `Space` | GO next cue |

## Demo
[Living room test](media/living-room-mapping-test.mp4)
