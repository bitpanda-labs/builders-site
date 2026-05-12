# Bitpanda Builders Website

🚀 **The official website for Bitpanda Builders** - documentation and tools for developers and AI builders connecting to Bitpanda.

[![Live Site](https://img.shields.io/badge/Live-builders.bitpanda.com-blue)](https://builders.bitpanda.com)
[![Static HTML](https://img.shields.io/badge/Built%20with-Static%20HTML-orange)](https://developer.mozilla.org/docs/Web/HTML)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-green)](https://pages.github.com/)

## 🌟 About

Bitpanda Builders is the developer hub for everything you can build on top of Bitpanda — the MCP server for AI agents, command-line tooling, and pre-built agent skills. This site documents how to connect, authenticate, and use those tools against your Bitpanda portfolio.

## 🚀 Quick Start

No build step or dependencies — the site is plain HTML/CSS. To preview locally:

```bash
git clone git@github.com:bitpanda-labs/builders-site.git
cd builders-site
python3 -m http.server 8080
```

Then open http://localhost:8080.

## 📁 Project Structure

```
├── index.html              # Hub homepage
├── 404.html                # Branded 404 page
├── mcp/
│   └── index.html          # MCP server documentation
├── assets/                 # Shared images
│   └── bitpanda-lettermark.png
├── favicon.svg
├── robots.txt
├── sitemap.xml
├── CNAME                   # Custom domain (builders.bitpanda.com)
└── .nojekyll               # Disable Jekyll processing on GitHub Pages
```

## 🚀 Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

- **Live URL:** [https://builders.bitpanda.com](https://builders.bitpanda.com)
- **Default Pages URL:** [https://bitpanda-labs.github.io/builders-site/](https://bitpanda-labs.github.io/builders-site/) (redirects to the live URL)

The custom domain is set via the `CNAME` file at the repo root, with a Cloudflare DNS record managed in [`bitpanda-production-zones`](https://gitlab.com/bitpanda/it-platform-sre/cloud/cloudflare/bitpanda-production-zones).

## 🤝 Contributing

We welcome contributions! Please:

1. **Fork the repository**
2. **Create a feature branch**
3. **Follow our standards:**
  - Match the existing design tokens and component patterns
  - Keep pages dependency-free (no JS frameworks, no build step)
  - Test locally before submitting
4. **Submit a pull request**

## 📝 License

This project is open source. Please check with Bitpanda Labs for specific licensing terms.

## 🔗 Links

- **Live Website:** [https://builders.bitpanda.com](https://builders.bitpanda.com)
- **Bitpanda:** [https://www.bitpanda.com/](https://www.bitpanda.com/)
- **Bitpanda Labs:** [https://labs.bitpanda.com](https://labs.bitpanda.com)
- **Bitpanda Developer API:** [https://developers.bitpanda.com](https://developers.bitpanda.com)

## 💬 Support

For questions or support:

- **Open an issue** in this repository
- **Contact Bitpanda Labs** through official channels

---

**Built with ❤️ by the Bitpanda Labs team**