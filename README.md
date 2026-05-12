# Bitpanda Builders Website

🚀 **The official website for Bitpanda Builders** - documentation and tools for developers and AI builders connecting to Bitpanda.

[![Live Site](https://img.shields.io/badge/Live-builders.bitpanda.com-blue)](https://builders.bitpanda.com)
[![Jekyll](https://img.shields.io/badge/Built%20with-Jekyll-red)](https://jekyllrb.com/)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-green)](https://pages.github.com/)

## 🌟 About

Bitpanda Builders is the developer hub for everything you can build on top of Bitpanda — the MCP server for AI agents, command-line tooling, and pre-built agent skills. This site documents how to connect, authenticate, and use those tools with a Bitpanda account.

## 🚀 Quick Start

### Prerequisites
- Ruby 3.x
- Bundler

### Local Development

1. **Clone the repository:**
   ```bash
   git clone git@github.com:bitpanda-labs/builders-site.git
   cd builders-site
   ```

2. **Install dependencies:**
   ```bash
   bundle install
   ```

3. **Run the development server:**
   ```bash
   bundle exec jekyll serve
   ```

4. **View the site:**
   Open [http://localhost:4000](http://localhost:4000) in your browser.

## 📁 Project Structure

```
├── _config.yml             # Jekyll configuration
├── _layouts/
│   └── default.html        # Shared page layout
├── _includes/
│   └── header.html         # Shared site header
├── index.html              # Hub homepage
├── 404.html                # Branded 404 page
├── mcp/
│   └── index.html          # MCP server documentation
├── assets/                 # Shared images
│   └── bitpanda-lettermark.png
├── favicon.svg
├── robots.txt
├── CNAME                   # Custom domain (builders.bitpanda.com)
└── Gemfile                 # Ruby dependencies
```

## 🚀 Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

- **Live URL:** [https://builders.bitpanda.com](https://builders.bitpanda.com)

## 🤝 Contributing

We welcome contributions! Please:

1. **Fork the repository**
2. **Create a feature branch**
3. **Follow our standards:**
   - Match the existing design tokens and component patterns
   - Keep pages dependency-light (no JS frameworks, no build step beyond Jekyll)
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
