# Mphele's Bakery (Multi-Page Static Website)

## What I added so far
This project is a multi-page, static website for **Mphele's Bakery** with a consistent look and navigation across all pages.

### Pages implemented
- **Home**: `index.html`
- **About**: `about.html`
- **Gallery / Services**: `service.html`
- **Contact**: `contact.html` (includes an embedded Google Map)
- **Booking / Enquiry**: `enquiry.html`
- **Category pages**:
  - `bread.html`
  - `cakes.html`
  - `muffins.html`
  - `cookies.html`

### Shared layout
- A **sticky top navigation bar** (`nav` + `.navbar`) with Font Awesome icons.
- Reusable **section cards** using the same background, border, and shadow styling.
- A consistent footer on each page.

## Styling (CSS)
All styling is located in:
- `assets/css/styles.css`

### Design highlights
- **Color theme with CSS variables** (`:root`):
  - Pink highlights (e.g. `--pink-1`, `--pink-2`)
  - Brown/gold accents (e.g. `--brown-1`, `--brown-2`)
  - Text/overlay colors and card styling
- **Gold + black “melt” gradient text**:
  - The gradient is defined as `--merge-grad`
  - Applied to headers (`h1`, `h2`) using `background-clip: text` and `color: transparent`
- **Dark glass-like sticky header**:
  - `backdrop-filter: blur(8px)`
  - Semi-transparent black background and border
- **Product/category card grid**:
  - `.product-grid` and `.product-card` for consistent tile sizing
  - Hover effects (lift + color/border shift)
- **Forms styling**:
  - Input/select/textarea/button share the same rounded + dark theme
- **Responsive design**:
  - Breakpoints at `max-width: 820px` and `max-width: 520px`
  - Adjusts section padding/margins, navbar spacing, and iframe height

## Fonts & Icons
### Font family
- The website uses a **system font stack** in `styles.css`:
  - `ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, "Noto Sans", "Liberation Sans", sans-serif`

### Icons
- **Font Awesome** is loaded from the CDN on each page:
  - `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css`

> Note: There is an `assets/fonts/` directory in the project, but the current CSS uses the system font stack (no custom font file is referenced in `styles.css`).

## How to run
Because this is a static website:
1. Open `index.html` in your browser.
2. Use the navigation links to move between pages.

## File structure (key files)
- `index.html`, `about.html`, `service.html`, `contact.html`, `enquiry.html`
- `bread.html`, `cakes.html`, `muffins.html`, `cookies.html`
- `assets/css/styles.css`
- `assets/images/` (category images)
- `assets/fonts/` (present in repo)
- `assets/js/` (if used by any page)

