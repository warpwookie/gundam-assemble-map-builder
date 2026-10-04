# Gundam Assemble Map Builder

A browser tool for laying out hex maps for the Gundam Assemble tabletop game.

**Use it:** https://warpwookie.github.io/gundam-assemble-map-builder/

## What it does

- Build a hex field of any size up to 26 × 26. Hexes are labeled row letter + column letter (AA, AB, AC…). Inset rows can be one hex shorter.
- Paint three layers onto each hex:
  - **Elevation** (outer band): E0 to E4
  - **Ground type** (inner hex): Basic ground, Water, Debris field, Minovsky Particles, Impassable, Space
  - **Map feature** (badge): Bases, Garrisons and Carrier starts for Player A and B, Objectives 1–4, Energy, Upgrade tokens, Shield / Speed / Strength Upgrades, Scenario tokens
- Place generic Upgrade tokens, then share them out evenly as Shield, Speed and Strength Upgrades (spread out or random). Redistribute or reset at any time.
- Paint, Erase and Copy tools, drag painting, undo, and one-click fills for open hexes.
- Show or hide hex labels, elevation tags, badge letters and the legend.
- Export a PDF (Letter, A4, Tabloid or A3, full color or ink saver), with an optional map list page.
- Save and reopen maps as `.json` files. The current map is also remembered in your browser.

## Notes

- Water, Debris fields, Minovsky Particles, Impassable Terrain and elevation come from the Gundam Assemble Core Rulebook v1.0. "Basic ground" and "Space" are visual labels only and have no rules effect in the core rulebook.
- The rulebook sets no maximum elevation; stopping at E4 is a choice made for this tool.
- This is an unofficial fan tool and is not affiliated with Bandai, Sunrise or the publishers of Gundam Assemble.

## Running locally

Open `index.html` in a browser. Everything is in that one file; the only external pieces are Google Fonts and the jsPDF library from cdnjs.
