# Stapleton Joinery — Measure & Quote V3.0

## Install / update (GitHub Pages)

Upload the **index.html** file from this package into the **root** of your working `stapleton-joinery-v2` repository on the `main` branch, replacing the current root `index.html`. Commit the change, wait for the Pages deployment to complete, then reopen the site in Safari (optionally add `?v=3` to the URL).

**Back up any jobs in the old app before updating.** V3 uses a new local storage key and doesn't automatically import V2 browser jobs. Download a backup from V2 before replacing it. V3's backup/restore format is its own format, not a guaranteed V2 migration.

### What works
- Customer job creation; multiple independent windows per job
- Four visual layouts: fixed, single sash, two sash, three sash
- Adjustable width, height, frame/sash face and section depths, glazing bars, opening direction
- Provisional dimensioned elevation (SVG)
- Simplified component and nominal glazing calculations
- Demo pricing, margin slider, editable demo rates and rate export
- iPhone photo capture, compressed browser-local photos
- Browser-local saving, JSON backup/restore and printable preliminary workshop sheet

### Limitations
- Not a cutting list, glazing order, structural design, or verified manufacturing drawing
- Timber estimates based on simplified perimeter calculations, not detailed sections or stock optimisation
- Glazing area is nominal; panes and rebate deductions require proper section rules
- Prices are made-up and no real quotes should be issued based on them
- Jobs are stored only on the current browser/device and can be lost if website data is cleared
- Public static GitHub Pages host has no secure account database or Xero sync
- No doors, staircases, 3D or customer quote sending yet
