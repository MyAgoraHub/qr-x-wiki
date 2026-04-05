# QR-X Wiki

A clean, minimal Docusaurus wiki for the QR-X project hosted on GitHub Pages.

## Quick Start

### Installation

```bash
npm install
```

### Local Development

```bash
npm start
```

The site will open at `http://localhost:3000`.

### Build

```bash
npm run build
```

Generates static content into the `build` directory.

### Deploy to GitHub Pages

1. Update `docusaurus.config.js`:
   - Set `organizationName` to your GitHub username/org
   - Set `projectName` to `qr-x-wiki`

2. Deploy:
   ```bash
   npm run deploy
   ```

## Structure

```
├── docs/                  # Documentation pages
│   ├── intro.md
│   ├── getting-started/
│   ├── features/
│   └── api/
├── src/                   # Custom components & styles
│   └── css/custom.css
├── static/                # Static assets
├── docusaurus.config.js   # Main config
├── sidebars.js            # Navigation structure
└── package.json
```

## Customization

- Edit `sidebars.js` to change navigation
- Update `docusaurus.config.js` for site title, URL, and colors
- Add docs in `docs/` folder following the sidebar structure
