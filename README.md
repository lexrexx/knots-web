# Knots Web - Static Site

A generated static website for [Bitcoin Knots](https://bitcoinknots.org/), built with Nuxt 4. This repository contains the compiled static files ready for deployment.

## 📋 Overview

This is a static version of the Bitcoin Knots website, generated from the source repository: [lexrexx/bitcoinknots.org](https://github.com/lexrexx/bitcoinknots.org). The site is built using Nuxt 4 and configured to be served from any top-level public directory (`/`).

## 🚨 Important Note

**This version of the generated site is for testing purposes only.** It should not be used for production deployments without proper verification and validation.

## 🏗️ Technical Details

- **Framework**: Nuxt 4
- **Build Type**: Static Site Generation (SSG)
- **Base URL**: `/` (can be served from any domain's root directory)
- **Deployment**: Ready for static hosting services (GitHub Pages, Netlify, Vercel, etc.)

## 🔗 Source Repository

The source code and development files are maintained in a separate repository:
- **Source**: [https://github.com/lexrexx/bitcoinknots.org](https://github.com/lexrexx/bitcoinknots.org)
- **Generated Site**: [https://github.com/lexrexx/knots-web](https://github.com/lexrexx/knots-web)

## 🚀 Deployment

This static site can be deployed to any static hosting service. The `baseURL="/"` configuration allows it to be served from:
- `https://bitcoinknots.org/`
- `https://example.com/`
- Or any other domain's root directory

### Simple Deployment Options:

1. **GitHub Pages**: Enable in repository settings
2. **Netlify**: Drag and drop the `dist/` folder
3. **Vercel**: Import repository
4. **Any static file server**: Serve the contents directly

## 📁 Project Structure

The generated site contains standard static files:
```
├── index.html          # Main entry point
├── _nuxt/              # Compiled assets (CSS, JS, images)
├── [other pages]/      # Additional static pages
└── [static assets]     # Other static resources
```

## 🛠️ Development & Regeneration

To regenerate this static site or make changes:

1. Clone the source repository:
   ```bash
   git clone https://github.com/lexrexx/bitcoinknots.org
   ```

2. Install dependencies and build:
   ```bash
   npm install
   npm run generate
   ```

3. The `dist/` folder will contain the generated static files (identical to this repository's contents).

## ⚠️ Testing Status

This deployment is intended for **testing purposes only**. Please verify all functionality and content before using in production environments.

## 📄 License

Same as the source repository. Please refer to the [source repository](https://github.com/lexrexx/bitcoinknots.org) for licensing information.

---

*For issues, contributions, or questions about the website content, please refer to the [source repository](https://github.com/lexrexx/bitcoinknots.org).*