# WordPress Setup

This repository contains Gutenberg/Site Editor source snippets rather than a complete installable theme.

## Site Logo

Upload `assets/branding/auto-parts-trading-logo.png` to the WordPress Media Library and set it as the global Site Logo. The header source uses the native `wp:site-logo` block, so the logo is intentionally not hard-coded into `header.html`.

## Header and Footer

Use the Site Editor template-part code editor to place:

- `components/header.html` into the site's Header template part.
- `components/footer.html` into the site's Footer template part.

Save the template parts globally.

## Pages

Create the required WordPress pages and paste the corresponding files through the WordPress Code editor:

- Home → `pages/home.html`
- About Us → `pages/about.html`
- Contact Us → `pages/contact.html`

Set the Home page as the static homepage under WordPress reading settings if required.

## Important

Before publishing, verify:

- Navigation URLs
- Logo/site-logo configuration
- Contact details
- Search behaviour
- Vehicle-registration CTA destination
- Any ecommerce/account/wishlist/basket links
- Mobile navigation
- WordPress template spacing

The repository deliberately excludes WordPress core files, plugins, databases, credentials and hosting configuration.
