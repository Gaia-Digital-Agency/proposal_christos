# Christos Medicine - Project Instructions

## Overview

This is a website project for Christos Medicine, a sacred platform devoted to compassion and embodied love. The project is currently in the **static HTML mockup phase**.

## Project Structure

```
christos_medicine/
├── mockup/                 # Current working mockup
│   ├── index.html          # Home page (root)
│   ├── pages/              # Subpages
│   │   ├── about.html
│   │   ├── offerings.html
│   │   └── contact.html
│   └── src/                # Assets
│       ├── styles.css      # All styles (includes dark/light themes)
│       └── script.js       # Theme toggle + smooth scroll
├── references/             # Design briefs and recommendations
└── readme.md               # Project documentation
```

## Key Design Elements

### Theme System
- **Light Theme**: Inspired by ellenrikhye.com - soft grays, rust-red accent (#af4b43)
- **Dark Theme**: Inspired by naclinicbali.com - warm blacks, gold accent (#d4b88b)
- Theme preference saved to localStorage and persists across pages

### Typography
- Headings: Cormorant Garamond (Google Fonts)
- Body: Inter (Google Fonts)

### Color Variables (CSS)
```css
/* Light */
--bg-color: #f4f4f4;
--text-color: #2d2d2d;
--accent-color: #af4b43;

/* Dark */
--bg-color: #1a1918;
--text-color: #f5f0e8;
--accent-color: #d4b88b;
```

## Development Notes

### File Path Conventions
- From `index.html`: reference pages as `pages/about.html`, assets as `src/styles.css`
- From pages in `pages/`: reference home as `../index.html`, assets as `../src/styles.css`, sibling pages directly as `about.html`

### Adding New Pages
1. Create HTML file in `/mockup/pages/`
2. Copy header/footer structure from existing page
3. Update navigation links and active state
4. Ensure correct relative paths to `../src/styles.css` and `../src/script.js`

### Modifying Themes
- All theme variables are in `styles.css` under `:root` and `[data-theme="dark"]`
- Theme toggle logic is in `script.js`

## Future Plans
The mockup will be converted to a WordPress Block Theme with:
- Full Site Editor (FSE) support
- `theme.json` for design tokens
- Reusable block patterns

## Reference Sites
- Dark theme inspiration: https://naclinicbali.com/
- Light theme inspiration: https://www.ellenrikhye.com/en/
