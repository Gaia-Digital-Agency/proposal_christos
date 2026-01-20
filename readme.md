**Creation Date:** 2024-05-24
**GitHub Remote:** `christos-medicine-website`
Developed by gaiada.com
Copyright (C) 2026

## App Title

**Christos Medicine** - A Sacred, Heart-Led Web Platform

## App Introduction

This project is the official website for Christos Medicine, a platform devoted to compassion, embodied love, and inner alignment. The website is designed to be a calm, sincere, and spacious online sanctuary, reflecting the essence of the work. It avoids a commercial feel, focusing instead on creating a space of presence and trust for visitors.

## Current Status

The project is currently in the **static HTML mockup phase**. A working prototype has been created to establish the visual design, layout, and user experience before development of the final WordPress Block Theme.

## Mockup Structure

```
/mockup/
├── index.html              # Home page
├── pages/
│   ├── about.html          # About Johannes
│   ├── offerings.html      # Services and offerings
│   └── contact.html        # Contact form and info
└── src/
    ├── styles.css          # All styles with dark/light theme
    └── script.js           # Theme toggle functionality
```

## Design Features

### Theme System
The mockup includes a dark/light theme toggle:

- **Light Theme** (inspired by ellenrikhye.com): Soft gray backgrounds, dark charcoal text, warm rust-red accent
- **Dark Theme** (inspired by naclinicbali.com): Deep warm black backgrounds, cream text, gold accent

### Typography
- **Headings:** Cormorant Garamond (elegant serif)
- **Body:** Inter (clean sans-serif)

### Pages
1. **Home:** Hero section, intro cards, quote, and call-to-action
2. **About:** Bio section with image placeholder, philosophy grid, background
3. **Offerings:** Service cards, media links, contact CTA
4. **Contact:** Contact form, contact methods, donation section

## How to View the Mockup

1. Open `/mockup/index.html` in a web browser
2. Use the sun/moon toggle button in the header to switch between light and dark themes
3. Navigate between pages using the navigation menu

## Future Development

The final implementation will be a **WordPress Block Theme** using:
- **CMS:** WordPress with Full Site Editor (FSE)
- **Languages:** PHP, JavaScript, HTML, CSS
- **Styling:** Managed via `theme.json` and custom block styles

### WordPress Theme Structure (Planned)
```
/wp-content/themes/christos-medicine-theme/
├── assets/         # CSS, JS, images, fonts
├── parts/          # Reusable HTML template parts (header.html, footer.html)
├── patterns/       # PHP files defining custom block patterns
├── templates/      # Main HTML page templates (index.html, page.html)
├── functions.php   # Theme logic and pattern registration
└── theme.json      # Global settings, styles, colors, typography
```

## Design Principles

- **UI/UX:** Minimal, spacious, and calm with clean typography and an earthy color palette
- **Mobile Friendly:** Fully responsive design for all devices
- **Accessibility:** Semantic HTML, proper contrast ratios, keyboard navigation support
- **Performance:** Lightweight CSS and minimal JavaScript

## Testing Checklist

- [ ] Cross-browser testing (Chrome, Firefox, Safari)
- [ ] Responsive design (mobile, tablet, desktop)
- [ ] Theme toggle persistence across pages
- [ ] All navigation links working correctly
- [ ] Form elements styled consistently in both themes
