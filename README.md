# Mela Shopify Theme

A Shopify Online Store 2.0 theme named "Mela", based on Shopify's Dawn 6.0.2 and connected to a store through Shopify's GitHub integration.

![Shopify](https://img.shields.io/badge/Shopify-Dawn%206.0-7AB55C?logo=shopify&logoColor=white) ![Liquid](https://img.shields.io/badge/Liquid-Templates-2C3E50)

## Overview

An early (2022) Shopify theme project used as the starting point for a custom storefront. The theme metadata is renamed to "Mela" (author HassAsraf); the sections, snippets and templates follow Dawn 6.0.2.

## Features

- Online Store 2.0 JSON templates with sections on every page
- Cart drawer, cart notification pop-up or cart page (configurable in theme settings)
- Header, footer, announcement bar, slideshow, image banner, image with text, multicolumn, collage, rich text, collapsible content, video, newsletter and email signup banner sections
- Featured collection, featured product, featured blog and collection list sections
- Product page with media gallery, 3D model/video support, pickup availability, product recommendations and quick add
- Collection filtering and sorting (facets), predictive search
- Customer account templates (login, register, account, addresses, orders)
- Multi-language locale files

## Tech Stack

- Shopify Liquid, Dawn 6.0.2
- CSS and vanilla JavaScript (web components)

## Getting Started

**Prerequisites:** [Shopify CLI](https://shopify.dev/docs/api/shopify-cli) and a Shopify store or development store.

```bash
git clone https://github.com/coderasraf/mela-shopify-custom.git
cd mela-shopify-custom
shopify theme dev --store your-store.myshopify.com
```

Use `shopify theme push` to upload it, or connect the repository through Shopify's GitHub integration.

## Project Structure

```text
mela-shopify-custom/
├── assets/       # CSS and JavaScript components
├── config/       # settings_schema.json (theme name "mela"), settings_data.json
├── layout/       # theme.liquid, password.liquid
├── locales/      # Translations
├── sections/     # Page sections
├── snippets/     # Reusable Liquid snippets and icons
└── templates/    # JSON templates (incl. customers/)
```

## License

Based on Shopify's Dawn theme. See [LICENSE.md](LICENSE.md) for Shopify's license terms.

## Author

Built by **Ashraf Siddik**, Shopify developer & CRO specialist.

- Website: [ashraf-siddik.com](https://ashraf-siddik.com)
- GitHub: [@coderasraf](https://github.com/coderasraf)
