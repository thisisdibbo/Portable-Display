# Portable Display

A 3D-printable enclosure for a DIY portable monitor. The design covers the complete housing: a front bezel frame, a rear cover, a driver-board bay with ventilation slots and port cut-outs along the top edge, and a fold-out kickstand with a hinge pin.

Modeled in Tinkercad and exported as STL — ready to slice and print, no repair pass needed.

## Preview

| Front | Back | Side |
|---|---|---|
| ![Front view](ScreenShot/Screenshot%202026-09-28%20224626.png) | ![Rear view](ScreenShot/Screenshot%202026-09-28%20224631.png) | ![Side view with kickstand](ScreenShot/Screenshot%202026-09-28%20224636.png) |

## Design overview

- **Panel size** — outer frame measures **343.6 × 182.4 mm**, sized around a 15-inch-class 16:9 LCD panel.
- **Two-shell build** — front bezel and rear cover close over the panel; screw bosses sit at the four corners of the bezel.
- **Driver-board bay** — a raised rear module houses the controller board, with a slotted vent array for passive cooling.
- **Port access** — openings along the top edge of the rear module for the board's HDMI / USB-C / power and button connections.
- **Kickstand** — a hinged arm on a cylindrical pin lets the display stand at a viewing angle and fold flat for transport.

## Files

All models are binary STL, in millimetres.

| File | Part | Bounding box (X × Y × Z, mm) |
|---|---|---|
| `3D File/Portable Display.stl` | Front bezel frame | 343.6 × 77.1 × 182.4 |
| `3D File/Portable Display (1).stl` | Rear cover with board window | 343.6 × 82.9 × 185.0 |
| `3D File/Portable Display (2).stl` | Driver-board housing (vents + ports) | 196.0 × 72.4 × 112.1 |
| `3D File/Portable Display (3).stl` | Kickstand arm | 16.4 × 30.0 × 72.2 |
| `3D File/Portable Display (4).stl` | Hinge pin | 5.4 × 5.4 × 4.9 |
| `3D File/Portable Display (5).stl` | Vented port strip | 90.0 × 8.0 × 15.0 |
| `ScreenShot/` | Render previews of the assembly | — |

## Printing notes

Starting point — tune to your own printer and filament:

- **Material:** PLA or PETG
- **Layer height:** 0.2 mm
- **Walls:** 3 perimeters
- **Infill:** 20 % (bump the kickstand and hinge pin to 40–60 %)
- **Supports:** needed on the port cut-outs and the hinge boss; the flat shells print support-free laid face down
- **Bed:** the bezel and rear cover are larger than a 220 × 220 mm bed — print them on a 350 mm-class printer, or split them before slicing

Dry-fit the bezel against your panel and the housing against your driver board before committing to a full print — panel and board dimensions vary between suppliers.

## License

Released under the [MIT License](LICENSE).

## Author

**Md. Mahin Rahman**
GitHub: [@thisisdibbo](https://github.com/thisisdibbo)
