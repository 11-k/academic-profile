# Academic Profile

Personal academic profile website built with [Hugo](https://gohugo.io/) and [HugoBlox Academic](https://hugoblox.com/).

## Quick Start

### Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) (v0.141.0+)
- [Go](https://go.dev/dl/) (1.19+)
- [Node.js](https://nodejs.org/) (20+)

### Local Development

```bash
# Install Node.js dependencies
npm install

# Download Hugo modules
hugo mod get -u

# Start development server
hugo server --disableFastRender
```

Visit `http://localhost:1313` to preview your site.

### Build for Production

```bash
hugo --minify
```

## Customization

- **Personal info**: Edit `data/authors/me.yaml`
- **Homepage layout**: Edit `content/_index.md`
- **Publications**: Add new folders in `content/publications/`
- **Navigation**: Edit `config/_default/menus.yaml`
- **Theme settings**: Edit `config/_default/params.yaml`
- **Avatar**: Replace `assets/media/authors/me.png`

## Deployment

Push to `main` branch to auto-deploy via GitHub Pages (see `.github/workflows/deploy.yaml`).
