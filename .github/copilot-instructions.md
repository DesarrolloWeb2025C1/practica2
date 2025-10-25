# AI Coding Agent Instructions for Web Development Project

## Project Overview
This is a basic web development project designed for teaching HTML and CSS fundamentals. The project implements a simple personal webpage with a consistent color scheme of light blue, white, and black.

## Project Structure
- `index.html`: Main HTML structure
- `styles.css`: All styling definitions
- `imges/`: Directory containing project images:
  - `logo-desarolloWeb.png`: Course logo
  - `unpaz_logo.png`: University logo
  - `michi.jpg`: Sample content image

## Key Design Patterns

### Layout Structure
The page follows a fixed layout pattern with:
1. Two-part navigation bar (`navbar-blanco` and `navbar-celeste`)
2. Three-column content layout using flexbox:
   - Left sidebar (28% width): Personal information
   - Center column (24% width): Main image
   - Right section (44% width): Text content
3. Fixed footer at bottom

### Styling Conventions
- Color palette:
  - Primary background: `#bbdefb`
  - Navigation: `#2980B9`
  - Footer: `#1565c0`
  - Sidebar: `#e3f2fd`
- Responsive units:
  - Padding uses `vw` for viewport-relative spacing
  - Images use percentage widths with max-width constraints
  - Font sizes use pixels (16px base)

### Interactive Elements
- Menu items have hover effects (color transition to `#008cc4`)
- Contact form inputs have focus states (border color: `#007BFF`)

## Development Workflow
1. Use VS Code with Live Server extension for development
2. Edit personal information in the sidebar section of `index.html`
3. Customize colors and spacing in `styles.css` (comments indicate customization points)

## Common Customization Points
Look for inline comments in `styles.css` marked with `/* */` for the most frequently modified properties:
- Header/navbar sizes
- Logo dimensions and positioning
- Color scheme
- Content layout proportions
- Text sizes and colors