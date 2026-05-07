# AGENTS.md - Richard Muia Portfolio

## Project Overview
Static portfolio website showcasing QA/testing expertise. No build system, databases, or frameworks—vanilla HTML5, CSS3, and vanilla JavaScript only.

## Architecture & Structure
- **index.html** - Main portfolio page with sections: header, work/projects, companies, about, blog, contact, footer
- **index.css** - Responsive styles using CSS variables and grid/flexbox
- **index.js** - Minimal interactivity: keyboard focus detection, back-to-top button
- **blog/** - Blog section content (QA testing insights)
- **images/** - Project screenshots, logos, favicons
- **fonts/** - Custom fonts (HK Grotesk, Jost)

## Build/Test Commands
- No build or test commands—static site served directly
- View locally: Open `index.html` in browser or use `python -m http.server 8000` (then visit localhost:8000)
- Deploy: Push to GitHub; site hosted on GitHub Pages or Surge.sh

## Code Style Guidelines
- **HTML**: Semantic HTML5, ARIA roles for accessibility (role="banner", role="main", role="contentinfo")
- **CSS**: CSS custom properties (--variables), mobile-first responsive design, BEM-like class naming (e.g., `.nav__item`, `.work__box`)
- **JavaScript**: Vanilla ES6+, const/let for variables, camelCase for functions, arrow functions preferred
- **Naming**: kebab-case for CSS classes, camelCase for JS variables/functions
- **Accessibility**: Keyboard navigation support, focus outlines, semantic HTML, alt text for images
- **Format**: 2-space indentation, no trailing whitespace
