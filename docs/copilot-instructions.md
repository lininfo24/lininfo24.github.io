# GitHub Copilot Instructions for This Project

## Purpose

This project uses the W3.CSS v5 Photo Template as the base for my personal website.  
Copilot should generate code consistent with this template’s structure, typography, spacing, and layout.

## Template Structure (Important)

The template includes:

- W3.CSS v5
- Google Font: Raleway
- Header with two-line title (“PHOTOGRAPHER” + name)
- Centered navigation bar inside header
- Two-column grayscale photo grid using `w3-row-padding` and `w3-half`
- Footer with Font Awesome icons

Copilot must preserve these patterns unless I explicitly ask to change them.

## Rules for Copilot

### 1. Framework

- Use **W3.CSS v5 only**.
- Do NOT generate Bootstrap, Tailwind, or other frameworks.
- Prefer W3.CSS utility classes (`w3-container`, `w3-padding`, `w3-row-padding`, `w3-half`, etc.).

### 2. Typography

- Use `"Raleway", Arial, sans-serif` for body and h1.
- Maintain `letter-spacing: 6px` for h1 unless I request otherwise.

### 3. Layout

- Keep the main wrapper:  
  `<div class="w3-content" style="max-width:1500px">`
- Maintain the two-column photo grid structure.
- Use W3.CSS spacing classes instead of inline styles when possible.

### 4. Images

- Use `style="width:100%"` or `w3-image`.
- Maintain grayscale look using `w3-grayscale`.
- Always include alt text.
- Use relative paths: `/assets/images/...`.

### 5. Navigation Bar

- Use `w3-bar w3-border`.
- Active link uses `w3-light-grey`.
- Keep centered inside header.

### 6. Footer

- Use `w3-container w3-padding-64 w3-light-grey w3-center w3-large`.
- Icons use `fa` classes + `w3-hover-opacity`.

### 7. JavaScript

- Only add JS when needed.
- Use vanilla JS.
- Keep scripts minimal and placed at the bottom of the page.

### 8. Accessibility

- Add descriptive alt text.
- Ensure color contrast meets WCAG AA.
- Use semantic HTML (`<header>`, `<main>`, `<footer>`).

### 9. GitHub Pages

- Use relative paths for all assets.
- Avoid absolute paths unless external.

## How Copilot Should Respond

When I ask Copilot to:

- “Create a new page using this template”
- “Add a new photo grid section”
- “Customize the header with my name”
- “Convert this into a W3.CSS layout”

Copilot should:

- Follow the template structure above
- Follow the design system
- Maintain W3.CSS conventions

## Example Prompts I Will Use

- “Using the template, create an About page with a centered intro section.”
- “Add a Projects page with a 3-column grid.”
- “Rewrite the header to include my personal branding.”
- “Replace the photo grid with my own images.”
