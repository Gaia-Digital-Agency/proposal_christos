**Creation Date:** 2024-05-24
**GitHub Remote:** `christos-medicine-website`
Developed by gaiada.com
Copyright (C) 2026

## App Title

**Christos Medicine** - A Sacred, Heart-Led Web Platform

## App Introduction

This project is the official website for Christos Medicine, a platform devoted to compassion, embodied love, and inner alignment. The website is designed to be a calm, sincere, and spacious online sanctuary, reflecting the essence of the work. It avoids a commercial feel, focusing instead on creating a space of presence and trust for visitors.

## App Architecture

The application is built as a monolithic system using a standard **LAMP/LEMP stack**. It runs a self-hosted **WordPress (.org)** instance, which serves as both the backend Content Management System (CMS) and the frontend rendering engine.

The core of the project is a lightweight, custom **WordPress Block Theme** that leverages the Full Site Editor (FSE) for maximum flexibility and client-side manageability.

## App Language and Frameworks

-   **CMS:** WordPress
-   **Languages:** PHP, JavaScript, HTML, CSS
-   **Styling:** Managed via `theme.json` and custom block styles.

## Required Pages

The website will consist of the following main pages:

1.  **Homepage:** A gentle and inviting welcome/introduction.
2.  **About Us:** Featuring a bio and a call to action.
3.  **Offerings:** Detailing the work, services, and links to social media.
4.  **Contact / CTA:** With simple contact options and a link for donations.

## App File Structure

The custom theme follows a modern block theme structure.

```
/wp-content/
├── themes/
│   └── christos-medicine-theme/
│       ├── assets/         # CSS, JS, images, fonts
│       ├── parts/          # Reusable HTML template parts (header.html, footer.html)
│       ├── patterns/       # PHP files defining custom block patterns
│       ├── templates/      # Main HTML page templates (index.html, page.html)
│       ├── functions.php   # Theme logic and pattern registration
│       └── theme.json      # Global settings, styles, colors, typography
└── plugins/
    ├── ... (Minimal plugins for caching, forms, image optimization)
```

## App Run Steps

1.  Set up a local or remote server environment (e.g., LAMP, LEMP).
2.  Install the latest version of WordPress.
3.  Clone this repository into the `/wp-content/themes/` directory.
4.  Activate the "Christos Medicine" theme from the WordPress admin dashboard under `Appearance > Themes`.
5.  Install the recommended plugins for caching and image optimization.
6.  Use the `Appearance > Editor` to build out pages and apply content.

## Suggested Testing

-   **Cross-Browser Testing:** Verify layout and functionality on Chrome, Firefox, and Safari.
-   **Responsive Design:** Test on various screen sizes, including mobile, tablet, and desktop.
-   **Content Editing:** Log in as an editor role and confirm that text, images, and block patterns can be easily updated by the client.
-   **Performance:** Run a Lighthouse audit to check for performance, accessibility, and SEO scores.

### System Behaviour Potentials

-   **Functionality:** The site provides a simple, clear user journey to discover information and make contact.
-   **Maintainability:** High. The client can perform most content updates without developer intervention. The use of a standard WordPress theme structure makes it easy for any WordPress developer to understand and extend.
-   **Scalability:** Good. The site can be scaled vertically by upgrading server resources. Future functionality (like a blog or e-commerce) can be added via the vast WordPress plugin ecosystem.
-   **Efficiency:** High. By using a minimal block theme and essential plugins for caching and image optimization, the site will be lightweight and fast-loading.

### Frontend Features Presence

-   **UI/UX:** The design is minimal, spacious, and calm, with clean typography and an earthy color palette to create an intuitive and gentle user experience.
-   **Mobile View Friendly:** Yes, the site is fully responsive and designed to work beautifully on all devices.
-   **Payment:** Not directly integrated. The site links to an external donation platform.
-   **SEO:** Basic SEO is handled by WordPress core. An SEO plugin can be added for more advanced control.

### System Design Elements Presence

-   **Application:** WordPress
-   **Database:** MySQL / MariaDB (Standard for WordPress)
-   **Firewall:** Managed at the hosting/server level.
-   **CDN Server:** Recommended for global traffic to improve asset loading times.
-   **Caching:** Implemented via a WordPress plugin (e.g., WP Rocket, FlyingPress) for page and browser caching.