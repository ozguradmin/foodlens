# What Am I Eating?

What Am I Eating? is an open-source food product analysis tool powered by OpenFoodFacts data.

This repository is being maintained as an English-first version. The existing Turkish production deployment is intentionally left untouched.

## Features

- Search products by name
- Search products by barcode
- Camera-based barcode scanning
- Nutrition summaries
- Nutri-Score explanations
- NOVA processing-level analysis
- Eco-Score visibility
- Ingredient review
- Food additive (E-number) analysis
- Data quality indicators

## Demo Deployment Target

Recommended English demo target:

- GitHub Pages
- Cloudflare Pages
- Netlify
- Vercel

A separate English deployment should be used instead of the Turkish production site.

## Data Source

OpenFoodFacts

https://world.openfoodfacts.org

## Technology

- HTML
- Vanilla JavaScript
- Tailwind CSS
- OpenFoodFacts API
- ZXing
- BarcodeDetector API

## Local Development

Clone the repository and open `index.html` in a browser, or deploy the static files to any static hosting provider.

## Roadmap

- Complete translation of remaining Turkish user-facing strings
- Improve accessibility text and metadata
- Add dedicated English deployment configuration
- Expand nutrition explanations

## License

MIT