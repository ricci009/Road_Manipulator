# Road Manipulator

## What this is
An interactive visual editor for `BgCurvedRoad` JSX components. Lets you plot, visualize, and drag control points to design smooth, connected road networks for a 2D/game scene.

## Files
- `road_manipulator.html` — the entire tool (single-file, no dependencies, open in browser)
- `example.md` — source JSX snippet used as the initial dataset

## Road data format
```jsx
<BgCurvedRoad points={[[x, y], [x, y], ...]} width={number} />
```
- Coordinate system: origin (0,0) at scene center; positive X = right, positive Y = down
- Width is in world units (thicker = major road)
- Curves are rendered as Catmull-Rom splines through all control points

## Tool features
| Feature | How |
|---|---|
| Select road/point | Click (Select mode) |
| Drag point | Click+drag in Select mode |
| Add point to road | Switch to Add Pt mode, click on road |
| Delete point | Right-click point, or Del Pt mode, or Delete key |
| Add new road | R key or Add Road mode, click points, double-click to finish |
| Delete road | ✕ button in road list |
| Pan | Middle-drag or Space+drag |
| Zoom | Scroll wheel |
| Edit coordinates numerically | Click a point → edit x/y fields in sidebar |
| Change road width | Width slider in sidebar |
| Import JSX | ⬆ Import button → paste JSX |
| Export JSX | ⬇ Copy button → copies to clipboard |
| Reset view | ⌖ View button or `0` key |

## Key decisions
- Catmull-Rom splines: chosen because they pass through all control points (no offset), giving intuitive editing
- Single HTML file: no build step, just open in browser
- Roads colored by index from a fixed palette for visual distinction
- Y-axis matches screen/CSS convention (positive = down), same as the game engine

## Common edit tasks
- **Connect two roads**: place the last point of one road exactly at the first point of the next (use numeric x/y inputs for precision)
- **Smooth a curve**: add more control points in the middle of a segment
- **Adjust road density near center**: drag the inner control points (typically ~35 units from origin on the main roads)
