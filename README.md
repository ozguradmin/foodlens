# What Am I Eating? (English Edition)

What Am I Eating? is an English-first food product analysis application powered by Open Food Facts data.

This repository is maintained as a separate English version. The Turkish live deployment must remain untouched.

## Features

- Product name search
- Barcode lookup
- Camera barcode scanning
- Nutri-Score analysis
- NOVA processing insights
- Ingredient review
- E-number additive explanations
- Data quality indicators

## English Demo Deployment

Recommended target: Cloudflare Pages.

1. Connect this GitHub repository.
2. Deploy the repository root as a static site.
3. Use a separate Pages project for the English version.
4. Do not reuse or modify the Turkish production deployment.

## Data Source

Open Food Facts: https://world.openfoodfacts.org

## Technology

- HTML
- Vanilla JavaScript
- Tailwind CSS
- Open Food Facts API
- ZXing

## Roadmap

- Continue translating remaining user-facing Turkish strings.
- Improve accessibility and metadata.
- Expand nutrition guidance.

## License

MIT