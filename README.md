# Auto Parts Trading | WordPress Website

A custom WordPress/Gutenberg front-end project for **Auto Parts Trading**, a UK automotive-parts business.

The project demonstrates a responsive ecommerce-style website experience built with custom Gutenberg-compatible HTML and CSS. It includes a branded header and navigation system, vehicle-registration call-to-action, product-search interface, responsive homepage sections, business information pages and a reusable footer.

## Live Website

**https://autopartstrading.co.uk**

> The live WordPress website may continue to evolve independently of this repository.

## Project Highlights

- Custom WordPress/Gutenberg-compatible layouts
- Responsive desktop, tablet and mobile design
- Ecommerce-style automotive visual language
- Vehicle registration call-to-action
- Search-focused header experience
- Reusable custom header and footer
- Homepage designed around automotive products and customer journeys
- About Us and Contact pages
- Mobile navigation and responsive spacing
- Custom HTML/CSS without dependence on a page-builder export

## Tech Stack

- WordPress
- Gutenberg / Site Editor
- HTML5
- CSS3
- Responsive Web Design

## Repository Structure

```text
auto-parts-trading-wordpress/
├── assets/
│   └── branding/
│       ├── auto-parts-trading-logo.png
│       └── auto-parts-branding-guide.png
├── components/
│   ├── header.html
│   └── footer.html
├── pages/
│   ├── home.html
│   ├── about.html
│   └── contact.html
├── docs/
│   ├── project-structure.md
│   ├── wordpress-setup.md
│   └── screenshots/
├── .editorconfig
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── README.md
└── SECURITY.md
```

## Using the Code in WordPress

The files are source snippets intended for a WordPress block-theme/Site Editor workflow rather than a complete installable WordPress theme.

Typical workflow:

1. Open the relevant page or template in WordPress.
2. Switch to the **Code editor**.
3. Paste the appropriate source file.
4. Save or update the page/template.
5. Configure the site's logo, navigation destinations and business details as required.

See [`docs/wordpress-setup.md`](docs/wordpress-setup.md) for more detail.

## Source Files

| File | Purpose |
| --- | --- |
| `components/header.html` | Main site header, search, navigation and vehicle-registration CTA |
| `components/footer.html` | Reusable site footer |
| `pages/home.html` | Main Auto Parts Trading homepage |
| `pages/about.html` | About Us page |
| `pages/contact.html` | Contact page |

## Brand Assets

The repository includes the original project branding assets used during the build:

- `assets/branding/auto-parts-trading-logo.png` — transparent high-resolution logo
- `assets/branding/auto-parts-branding-guide.png` — visual logo/brand reference sheet

The WordPress header intentionally uses the native `wp:site-logo` block rather than hard-coding an image path. Upload `auto-parts-trading-logo.png` to WordPress and assign it as the Site Logo.

Most interface icons are inline SVGs embedded directly in the HTML source. Automotive photography used by the page designs is referenced from external Unsplash URLs rather than redistributed as local project assets; see `docs/external-assets.md`.

## Screenshots

Design/reference screenshots are included in `docs/screenshots/`, and additional live-site captures can be added later. Recommended captures:

- Desktop homepage
- Mobile homepage
- Header/navigation
- About page
- Contact page

## Open Source

Released under the [MIT License](LICENSE).

## Author

**Yash Bhatt**

GitHub: [@yash0908-bhat](https://github.com/yash0908-bhat)

---

This repository contains the front-end implementation and documentation for portfolio/open-source purposes. WordPress hosting configuration, customer records, payment information, credentials and other private production data are intentionally excluded.
