# pin-2k26

Design assets for the BalCCon 2k26 PCB-style pin/badge.

## Structure

- `svg/` — vector source files (Inkscape)
  - `pcb-only.svg` — final PCB-only artwork
  - `logo2k26_08.08-original.svg` — original full logo artwork
  - `pcb-assets.svg`, `pcb-decomposed.svg`, `date.svg` — decomposed/layered PCB artwork elements
- `png/colors/` — rendered color variants (black, blue, green, purple, red, white, yellow)
- `png/swatches/` — small reference color swatches (FR4 board color, grey)
- `balccon-2k26-hardware/` — KiCad project for the physical pin/badge PCB (schematic, board, routed and with silkscreen finished)
  - `pcb-svg/` — SVG layers exported from KiCad (`copper.svg`, `mask-front.svg`, `mask-back.svg`, `silkscreen-front.svg`, `esge-cuts.svg`, `hex.svg`, `log.svg`, `date.svg`)
  - `fabrication/` — Gerber and drill files exported for board fabrication
