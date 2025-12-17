# GrumpiFied_Designs

Mirrored site for GrumpiFied Designs Merch Site - Built with Astro and Spreadshop integration.

## Features

- **Dark Theme**: Clean, modern design with #111 background and white text
- **Spreadshop Integration**: Displays products from GrumpiFied Spreadshop using their .JS integration
- **Responsive Design**: Mobile-friendly layout with adaptive breakpoints
- **Fast Performance**: Built with Astro for optimal static site generation

## Development

### Prerequisites

- Node.js 18+ 
- npm

### Setup

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Spreadshop Configuration

The site is configured to display products from:
- **Shop Name**: GrumpiFied
- **Shop URL**: https://grumpified.myspreadshop.com
- **Locale**: us_US

Products are automatically loaded into the `#myShop` container on the homepage.

## Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── BaseLayout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── package.json
└── tsconfig.json
```
