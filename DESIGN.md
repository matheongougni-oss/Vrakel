---
name: Mineral Restraint & Laboratory Precision
colors:
  surface: '#131312'
  surface-dim: '#131312'
  surface-bright: '#3a3938'
  surface-container-lowest: '#0e0e0d'
  surface-container-low: '#1c1c1a'
  surface-container: '#20201e'
  surface-container-high: '#2a2a29'
  surface-container-highest: '#353533'
  on-surface: '#e5e2df'
  on-surface-variant: '#c8c7be'
  inverse-surface: '#e5e2df'
  inverse-on-surface: '#31302f'
  outline: '#919189'
  outline-variant: '#474741'
  surface-tint: '#c8c6c0'
  primary: '#ffffff'
  on-primary: '#30312c'
  primary-container: '#e4e2dc'
  on-primary-container: '#65655f'
  inverse-primary: '#5f5f59'
  secondary: '#cac6bc'
  on-secondary: '#323029'
  secondary-container: '#49473f'
  on-secondary-container: '#b9b5ab'
  tertiary: '#ffffff'
  on-tertiary: '#31302e'
  tertiary-container: '#e5e2de'
  on-tertiary-container: '#656461'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e4e2dc'
  primary-fixed-dim: '#c8c6c0'
  on-primary-fixed: '#1b1c18'
  on-primary-fixed-variant: '#474742'
  secondary-fixed: '#e7e2d8'
  secondary-fixed-dim: '#cac6bc'
  on-secondary-fixed: '#1d1c15'
  on-secondary-fixed-variant: '#49473f'
  tertiary-fixed: '#e5e2de'
  tertiary-fixed-dim: '#c9c6c3'
  on-tertiary-fixed: '#1c1c1a'
  on-tertiary-fixed-variant: '#474744'
  background: '#131312'
  on-background: '#e5e2df'
  surface-variant: '#353533'
typography:
  display-xl:
    fontFamily: Barlow Condensed
    fontSize: 5rem
    fontWeight: '800'
    lineHeight: '0.95'
    letterSpacing: 0.08em
  display-xl-mobile:
    fontFamily: Barlow Condensed
    fontSize: 3.25rem
    fontWeight: '800'
    lineHeight: '1.0'
    letterSpacing: 0.06em
  headline-lg:
    fontFamily: Barlow Condensed
    fontSize: 3.5rem
    fontWeight: '700'
    lineHeight: '1.05'
    letterSpacing: 0.06em
  headline-lg-mobile:
    fontFamily: Barlow Condensed
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: 0.05em
  headline-md:
    fontFamily: Barlow Condensed
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: '1.15'
    letterSpacing: 0.05em
  headline-sm:
    fontFamily: Barlow Condensed
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.04em
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.8'
    letterSpacing: 0.01em
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.75'
    letterSpacing: 0.01em
  body-sm:
    fontFamily: IBM Plex Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: '1.65'
    letterSpacing: 0.02em
  label-lg:
    fontFamily: IBM Plex Mono
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.12em
  label-md:
    fontFamily: IBM Plex Mono
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0.15em
  label-sm:
    fontFamily: IBM Plex Mono
    fontSize: 0.6875rem
    fontWeight: '400'
    lineHeight: '1.3'
    letterSpacing: 0.18em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 2rem
  space-xl: 3.5rem
  space-2xl: 6rem
---

## Brand & Style

This design system establishes an uncompromising dialogue between mineral brutalism, pharmaceutical restraint, and editorial space. Drawing direct inspiration from the stoic, monolithic geometry of Rick Owens, the apothecary cataloging method of Le Labo, and the structural breathing room of Aesop, the interface behaves like an architectural exhibition catalog or an analytical formulation manifest.

The aesthetic philosophy centers on absolute reduction, sculptural balance, and structural honesty:
- **Atmospheric Tension:** Surfaces alternate between pure, deep carbon mass (`#0B0B0A`) and tactile, tactile paper ivory (`#F0EEE7`), producing an immediate sense of weight, density, and deliberate calibration.
- **Instrumental Precision:** The interface does not hide its structural scaffolding. Fine hairline dividers (1px), subtle registration crosses (`+`), specimen index markings (`REF. 001`, `INDEX //`), and tabular alignments operate like an industrial formulation sheet.
- **Architectonic Purity:** Zero border radius everywhere. No rounded corners, no soft decorative pill shapes, and no superfluous dropshadows. Shapes are uncompromising slabs, monolithic blocks, and sharp spatial cuts.
- **Controlled Voice:** Typography acts as structural stone carving. Headlines are tall, compressed, and authoritative; body text provides intellectual legibility; micro-labels and specifications introduce laboratory technicality.

## Colors

The color palette is deliberately austere, anti-vibrant, and material-driven, referencing quarried stone, darkened basalt, lab-grade amber glass, and raw heavy-weight art paper.

### Palette Architecture
- **Noir Minéral (`#0B0B0A`):** The primary canvas ground in default dark state. Dense, deep, and light-absorbing like obsidian stone.
- **Ivoire Papier (`#F0EEE7`):** The primary signal, type color, and inverted canvas ground. Warm, unbleached, reminiscent of archival rag cotton paper and formulation labels.
- **Gris Pierre (`#8C8980`):** The neutral mediator, used for hairline rules, technical coordinate crosshairs, inactive states, and muted technical metrics.
- **Asphalte Fumé (`#1B1B19`):** Subtle container ground, providing depth differentiation for layered cards and specimen inspection panels without breaking the monolithic black plane.

### Application Rules
1. **Zero Decorative Color:** Functional indicators do not use bright chromatic reds or greens. Errors, status alerts, and confirmations are distinguished via high-contrast monochrome inversion, architectural brackets (`[ ! ]`), and strict typographic framing.
2. **Hairline Subordination:** Dividers and grid rules must use `#8C8980` at reduced opacity (`rgba(140, 137, 128, 0.25)` to `rgba(140, 137, 128, 0.45)`), ensuring structural guidance never overpowers content hierarchy.
3. **Inversion as Highlighting:** Critical focus states and selected states operate through total field inversion: ivory backgrounds with solid mineral black text.

## Typography

The typographic system is built on a tripartite tension:
1. **Monolithic Authority (Barlow Condensed):** Headlines are rendered exclusively in uppercase, with bold to extra-bold weights and expanded letter-spacing. They establish tall, physical boundaries reminiscent of concrete pillars or typographic stamps.
2. **Editorial Breathing (IBM Plex Sans):** Body text prioritizes calm intellectual immersion. Generous line heights (`1.75` to `1.8`) provide spacious reading tracks inspired by literary and apothecary monographs.
3. **Formulation Metadata (IBM Plex Mono):** All auxiliary metadata, references, product codes, volumetric tags, and navigational micro-copy use monospaced letterforms set in uppercase with exaggerated tracking.

### Formatting Directives
- Display and headline strings must be rendered in `text-transform: uppercase`.
- Mono labels and technical notations must never collapse letter spacing; ensure generous tracking (`0.12em` to `0.18em`).
- Numerical values tied to catalogs or indexes should be zero-padded to three digits (`001`, `002`, `014`) to maintain laboratory consistency.

## Layout & Spacing

The spatial discipline enforces architectural poise. Generous negative space frames high-density data nodules, avoiding visual clutter while demanding reverence for each element.

### Grid & Breakpoints
- **Desktop (1024px+):** 12-column rigid grid with a `3rem` canvas margin and `1.5rem` gutters. Outer borders and division lines often pin precisely to column edges.
- **Tablet (768px – 1023px):** 8-column layout with `2rem` margin and `1.25rem` gutters.
- **Mobile (< 768px):** 4-column layout with `1.25rem` margin and `1rem` gutters. Multi-column laboratory tables stack into vertically sequenced specimen cards separated by hairline rules.

### Spatial Rhythm
- **Rhythm Multiplier:** Layout spaces scale from an uncompromising 8px/4px base, expanding into monumental gaps (`space-xl`, `space-2xl`) between sections to honor the editorial stillness of gallery installations.
- **Hairline Framing:** Columns and major panels are bounded by fine 1px vertical and horizontal dividing borders, making the structural scaffolding part of the visual composition.

## Elevation & Depth

This system outright rejects drop shadows, Gaussian blurs, and skeuomorphic bevels. Visual depth is strictly mechanical and planar:

### Principles of Depth
- **Zero-Shadow Orthogonality:** No `box-shadow` or ambient lighting is permitted. The interface is completely flat, operating like an architectural section plan or etched printing plate.
- **Planar Tiering via Tone:**
  - Base ground: `Noir Minéral` (`#0B0B0A`).
  - Elevated surfaces / Specimen blocks: `Asphalte Fumé` (`#1B1B19`).
  - Active highlights / Overlays: Solid paper ground `Ivoire Papier` (`#F0EEE7`) with contrasting dark content.
- **Precision Hairlines:** Separation is created exclusively through 1px border lines using `Gris Pierre` at varying opacities (`rgba(140, 137, 128, 0.25)` base, rising to `rgba(240, 238, 231, 0.8)` on hover/focus).
- **Cartographic Overlays:** Popovers and technical flyouts are rendered as opaque rectilinear boxes framed with 1px solid borders, directly adjacent to crosshair reference axes.

## Shapes

The geometric vocabulary is absolute:
- **Strict Angles:** All radii are `0px` (`border-radius: 0 !important`). Every button, input, dialogue, card, badge, and image container terminates in sharp 90-degree corners.
- **Rectangular Monoliths:** Containers mirror cut stone blocks and pharmaceutical packaging cartons.
- **Geometric Orthogonality:** Lines are strictly vertical or horizontal; angled decorative ribbons or diagonal slices are prohibited.

## Components

### Buttons & Interactive Triggers
- **Primary Action:** Rectangular slab, filled solid with `Ivoire Papier` (`#F0EEE7`), text in bold uppercase Barlow Condensed or IBM Plex Mono in `Noir Minéral` (`#0B0B0A`). Height: 48px or 56px.
- **Secondary / Ghost Action:** 1px hairline border in `Gris Pierre` (`#8C8980`), transparent background, text in `Ivoire Papier`. On hover: full inversion (background becomes `#F0EEE7`, text `#0B0B0A`).
- **Paddings:** Strictly horizontal (`px: 2rem`, `py: 0.875rem`).
- **Corner Radius:** `0px`.

### Inputs & Formulation Fields
- **Container Style:** Rectangular box with dark ground (`#1B1B19`) or bottom-line only underline (1px `#8C8980`).
- **Typography:** Value input in IBM Plex Sans (16px), label positioned top-left in uppercase IBM Plex Mono (11px, tracked out).
- **Focus State:** Border transitions to solid `#F0EEE7` with a discreet monospaced indicator (`[ACTIVE]`) or technical crosshair pinned to the right edge.

### Chips & Specification Tags
- **Geometry:** Sharp rectangular tags without curves.
- **Appearance:** Enclosed in a 1px border of `rgba(140, 137, 128, 0.4)`. Background `#0B0B0A`.
- **Text:** IBM Plex Mono, 11px uppercase, zero-padded prefix (e.g., `[ 01 // CITRUS ]`).
- **Selected State:** Filled with `#F0EEE7`, text in `#0B0B0A`.

### Cards & Specimen Displays
- **Boundary:** Single hairline outline (1px `Gris Pierre` opacity 25%).
- **Header Structure:** Includes a top technical strip with index number (`REF 001`), timestamp, or batch reference left-aligned, and geometric status cross (`+`) right-aligned.
- **Imagery:** Monochromatic, high-grain, high-contrast packshots framed flush against sharp borders.

### Lists & Archival Tables
- **Dividers:** Continuous 1px horizontal hairline between rows.
- **Columns:** Monospaced tabular figures aligned strictly to numerical decimal points or right margins.
- **Hover State:** Row background shifts smoothly to `#1B1B19` with a left margin tick mark (`>`) emerging in `Ivoire Papier`.

### Checkboxes & Selectors
- **Box Shape:** 16px × 16px square, 0px border radius, 1px solid border (`#8C8980`).
- **Checked State:** Solid fill `#F0EEE7` containing a solid inner square of `#0B0B0A` (or total fill with an architectural `X` composed of crisp hairlines).