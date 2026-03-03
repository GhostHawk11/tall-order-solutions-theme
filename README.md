# Tall Order Solutions Theme

A modern, responsive Shopify theme for the Tall Order Solutions storefront.

## Features

- ✅ Responsive design (mobile-first)
- ✅ Customizable sections
- ✅ Product showcase
- ✅ Shopping cart
- ✅ Newsletter signup
- ✅ SEO optimized
- ✅ Fast loading

## File Structure

```
tall-order-solutions-theme/
├── config/
│   ├── settings_schema.json
│   └── settings_data.json
├── layout/
│   └── theme.liquid
├── sections/
│   ├── header.liquid
│   ├── footer.liquid
│   ├── hero.liquid
│   ├── featured-products.liquid
│   └── newsletter.liquid
├── templates/
│   ├── index.liquid
│   ├── product.liquid
│   ├── collection.liquid
│   ├── cart.liquid
│   └── page.liquid
├── snippets/
│   ├── product-card.liquid
│   └── price.liquid
├── assets/
│   ├── style.css
│   └── script.js
├── locales/
│   └── en.default.json
└── README.md
```

## Getting Started

1. Clone this repository
2. Install [Shopify CLI](https://shopify.dev/themes/tools/cli)
3. Run `shopify theme dev` to preview locally
4. Customize sections as needed
5. Push to Shopify when ready

## Customization

### Colors
Edit `assets/style.css` to change colors. Primary color is `#667eea`.

### Sections
Add or modify sections in the `sections/` directory. Each section can have its own settings schema.

### Products
Create a featured collection in Shopify admin and it will appear on the homepage.

## Support

For support, contact: Ghost_hawk11@proton.me

## License

© 2026 Tall Order Solutions. All rights reserved.