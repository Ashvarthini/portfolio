---
name: Midnight Portfolio
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#1f1f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c1c7d3'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#8b919d'
  outline-variant: '#414751'
  surface-tint: '#a4c9ff'
  primary: '#a4c9ff'
  on-primary: '#00315d'
  primary-container: '#4d93e5'
  on-primary-container: '#002a51'
  inverse-primary: '#0060ac'
  secondary: '#a5da2d'
  on-secondary: '#253600'
  secondary-container: '#8bbe00'
  on-secondary-container: '#334800'
  tertiary: '#ffb953'
  on-tertiary: '#452b00'
  tertiary-container: '#c58305'
  on-tertiary-container: '#3c2500'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#a4c9ff'
  on-primary-fixed: '#001c39'
  on-primary-fixed-variant: '#004883'
  secondary-fixed: '#bdf447'
  secondary-fixed-dim: '#a2d729'
  on-secondary-fixed: '#141f00'
  on-secondary-fixed-variant: '#374e00'
  tertiary-fixed: '#ffddb4'
  tertiary-fixed-dim: '#ffb953'
  on-tertiary-fixed: '#291800'
  on-tertiary-fixed-variant: '#633f00'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
typography:
  display-hero:
    fontFamily: Archivo Narrow
    fontSize: 84px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Archivo Narrow
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Archivo Narrow
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.2'
  subtitle:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system is built upon a foundation of **High-Contrast Minimalism**. It is designed for creative professionals and portfolios where the work needs to stand out against a void-like backdrop. The aesthetic is sophisticated yet bold, utilizing extreme tonal shifts to create visual impact.

The personality is confident, modern, and direct. It rejects superfluous decoration in favor of structural clarity and strong typographic hierarchies. The "Midnight" aesthetic ensures that photography and media are the primary focus, while the UI provides a high-end, gallery-like framing.

## Colors

The palette is strictly anchored in a true black (`#000000`) environment to maximize the vibrancy of the content. 

- **Primary Blue:** A medium-bright blue used sparingly for emphasis on specific keywords and professional identity.
- **Secondary Lime:** A high-visibility lime green used for "micro-moments" of delight or specific calls to action.
- **Neutrals:** White is used for primary headlines to provide maximum legibility, while mid-greys are used for supporting metadata and secondary information to reduce visual noise.

## Typography

The typography system relies on a high-contrast pairing between a condensed, bold display face and a neutral, systematic sans-serif.

- **Headlines:** Use **Archivo Narrow** (or a similar high-impact sans-serif). Bold weights are used for names and primary titles, while lighter weights are used for professional titles to create a clear "Hero" hierarchy.
- **Body & UI:** **Inter** provides a clean, functional counterpoint. It is used for all long-form text, navigation links, and small metadata.
- **Styling Note:** Use "Mixed Weight" headers (e.g., Medium + Bold in the same line) to emphasize specific parts of a name or title.

## Layout & Spacing

The layout follows a **Rigid Grid** philosophy that transitions from a multi-column desktop view to a single-column mobile stack.

- **Desktop Grid:** A 12-column grid is used for layout, but content typically adheres to a 3-column "Gallery" structure (each item spanning 4 columns). 
- **Gaps:** Gutters between images should be tight (24px) to create a cohesive visual block of work.
- **Vertical Rhythm:** Large vertical gaps (120px+) are used between major sections (Hero, Project Grid, Client Logos) to allow the design to "breathe" and signal a change in content type.
- **Alignment:** Content is primarily center-aligned for hero and footer sections, while the project grid remains edge-to-edge within the container.

## Elevation & Depth

This design system is intentionally flat. Depth is achieved through **Tonal Separation** rather than shadows.

- **Surface Tiers:** The background is always pure black. Interactive elements or cards do not use elevations; they rely on the content within them (images) to provide depth.
- **Dividers:** Horizontal rules are used sparingly. When used, they should be extremely subtle (low-opacity white) and vary in width to indicate hierarchy (e.g., a short line vs. a full-width line).
- **Overlays:** No backdrop blurs or glassmorphism are used. Information is either "on" or "off" the black canvas.

## Shapes

The shape language is **Sharp**. This reinforces the brutalist, architectural feel of the portfolio.

- **Images:** All project thumbnails must have 0px border-radius.
- **Icons:** Social media icons are contained within circular strokes to provide a organic contrast to the square grid above, but all functional UI containers remain rectangular.
- **Buttons:** If buttons are introduced, they should be sharp-edged or rely on text-only links with underlines.

## Components

### Project Grid
A dense layout of aspect-ratio-locked images. Images should be high-quality and fill the container entirely. On hover, a simple opacity change or the appearance of a project title is permitted.

### Client Logos
Displayed in a single or multi-row "ticker" style. All logos must be converted to flat white to maintain visual harmony and prevent brand colors from clashing with the system.

### Social Footer
Circular outlined icons (24px - 32px diameter). The stroke should be 1px white. Icons are centered and spaced evenly.

### Horizontal Rules
Used as section breaks or to separate the footer. Use a hierarchy:
- **Primary:** Full width, 1px, 10% white opacity.
- **Secondary:** 40px width, 2px, 30% white opacity (used for stylistic decoration).

### Typography Labels
Small tags (like the "product" label) use a specific accent color (Primary Blue) but maintain the same font size and weight as the surrounding text to keep the line-height consistent.