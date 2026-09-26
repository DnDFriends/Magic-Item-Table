# D&D Friends 5.5 Magic Item Guide

Deploy the contents of this folder at the root of a GitHub Pages site. Keep the `assets/` folder next to `index.html`; the Bear theme art loads from it.

## September 26, 2026 — new themes

- **Crooked Moon** (under Additional Themes): Crooked black page, dark blue-slate panels, Crooked blue borders and hover, moon-blue secondary text, gold accent, and yellow attunement items. The given brand colors are kept exactly for the page, panels, accent and attunement color; every text color passes WCAG AA (4.5:1), with Preserve MIT colors on or off.
- **Phoenix** (under Additional Themes): ember reds and flame oranges, carried over from the Allowed and Banned Content Guide.

## September 2026 usability and accessibility update

- **Phones:** new visitors on small screens start in the phone layout. The top bar uses two rows, so Filter, Text Size, Purchase List and More are always on screen. The floating Theme button is gone; Theme is in More.
- **Desktop top bar:** buttons that don't fit move into More one at a time, starting with the least used. The live-data status shows when there is room, and it is always listed at the top of More.
- **Search tab:** has its own search box and item count.
- **Search & Filter:** shows how many items match, with a "Show only matches" link. The Compare Mode checkbox now sits next to its label.
- **Touch screens:** ★ / + / compare buttons are always visible and don't cover item names.
- **Purchase list:** items already on the list get a green edge in the table. The wallet boxes match the other inputs, and the points summary no longer splits "T4:0" across lines.
- **Drawers and dialogs:** the drag-table bar and tier buttons are hidden while a drawer or dialog is open. Reset now offers Undo for 10 seconds.
- **Accessibility:**
  - All 45 themes, with Preserve MIT colors both on and off, pass WCAG AA text contrast (4.5:1) on the tables, drawers and filter panel, on desktop and phone.
  - Light themes now use a darker MIT orange for attunement items.
  - Attunement items carry a ◆ marker, so they aren't marked by color alone. It can be turned off under Text Size.
  - Dialogs are labeled for screen readers, keyboard focus is always visible, and reduced-motion settings are respected.
- **Google Sheet checks:** the page checks the Sheet once a minute (was every 15 seconds), only while the tab is visible. Returning to the tab triggers a check only if the last one was more than 30 seconds ago.
- **File size:** `index.html` went from about 1.0 MB to 0.69 MB, because the Bear theme art now loads from `assets/` instead of being embedded.
