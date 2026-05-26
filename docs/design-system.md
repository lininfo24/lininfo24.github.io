# Design System for My Personal Website

## Brand Personality

Clean, modern, minimal, photography-inspired, elegant.

## Typography

### Global

- Font: "Raleway", Arial, sans-serif

### Headings

- Use W3.CSS heading sizes (`w3-xlarge`, `w3-xxlarge`, etc.)
- h1 uses letter-spacing: 6px (template default)

### Body Text

- Font: Raleway
- Weight: 400
- Line height: 1.6

## Color Palette

### Primary

- Primary Blue: #3C8DBC
- Primary Dark: #2C3E50

### Accent

- Accent Coral: #FF6F61

### Neutrals

- Light Gray: #F5F5F5
- Medium Gray: #CCCCCC
- Dark Gray: #333333

## Layout Rules

- Main wrapper: `w3-content` with max-width: 1500px.
- Use W3.CSS spacing classes (`w3-padding-32`, `w3-margin-top`).
- Keep sections visually separated with padding and light backgrounds.

## Components

### Header

- Centered text.
- Two-line title (role + name).
- Navigation bar inside header using:
  - `w3-bar w3-border`
  - Active link: `w3-light-grey`

### Photo Grid

- Two columns using:
  - `w3-row-padding`
  - `w3-half`
- Images:
  - `style="width:100%"`
  - `w3-grayscale`
  - `margin-bottom: 12px`
- Maintain vertical rhythm.

### Cards (for About/Projects)

- Use `w3-card`, `w3-round`, `w3-padding`.
- Shadow: `w3-card-4`.

### Footer

- Light grey background.
- Centered Font Awesome icons.
- Use `w3-hover-opacity`.

## Accessibility Rules

- All images must have descriptive alt text.
- Links must have meaningful labels.
- Colors must meet contrast guidelines.
