# builders-site

Source for [builders.bitpanda.com](https://builders.bitpanda.com) — documentation and tools for developers and AI builders working with Bitpanda.

Hosted as a static site on GitHub Pages.

## Structure

```
.
├── index.html              Hub homepage
├── mcp/index.html          MCP server docs
├── assets/                 Shared images
├── favicon.svg
├── CNAME                   Custom domain (builders.bitpanda.com)
└── .nojekyll               Disable Jekyll processing on GitHub Pages
```

## Local development

```sh
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Deployment

Pushes to `main` are published automatically by GitHub Pages.
