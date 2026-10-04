<div align="center">

# Kome WebCore — Astro + Sveltia CMS Starter for Fast Jamstack Websites

**Shared, production-ready Astro (AstroWind) + Sveltia CMS codebase powering [komestudio.com](https://komestudio.com) and [kome.top](https://kome.top).**

[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](./LICENSE)
[![Astro](https://img.shields.io/badge/Astro-static%20site-BC52EE?logo=astro&logoColor=white)](https://astro.build)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38BDF8?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-ready-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Cloudflare Pages](https://img.shields.io/badge/Deploy-Cloudflare%20Pages-F38020?logo=cloudflare&logoColor=white)](https://pages.cloudflare.com)

[🌐 Kome Studio](https://komestudio.com) · [🔗 Kome Top](https://kome.top) · [🐞 Report an issue](https://github.com/KomeStudio/WebCore/issues)

</div>

---

## About

**Kome WebCore** is the shared website engine behind the Kome ecosystem. It combines **Astro** (via the **AstroWind** template), **Tailwind CSS**, **TypeScript** and **Sveltia CMS** (a Git-based headless CMS) into a fast, SEO-friendly static site that deploys for free on **Cloudflare Pages**.

One codebase, multiple sites: each site keeps its own content, branding and config, while core components, layouts and SEO logic are maintained in one place.

| Site | Purpose |
| --- | --- |
| [**komestudio.com**](https://komestudio.com) | Official website of **Kome Studio** — indie game studio: games, news and company info. |
| [**kome.top**](https://kome.top) | Kome portal — gateway to projects, resources and guides. |

## Features

- ⚡ **Blazing fast** — static output, zero JS by default, excellent Lighthouse / Core Web Vitals scores.
- 🔍 **SEO built in** — meta tags, Open Graph, Twitter Cards, canonical URLs, XML sitemap, RSS feed, `robots.txt` and structured data (JSON-LD).
- 📝 **Git-based headless CMS** — edit content visually with **Sveltia CMS**; no database, no server.
- 🎨 **Tailwind CSS** — responsive, dark-mode-ready, easy to rebrand.
- 🖼️ **Image optimization** — automatic resizing and modern formats (WebP/AVIF).
- 🧱 **Reusable widgets** — hero, features, pricing, FAQ, blog, contact and more.
- 🌍 **Multi-site ready** — reuse the same core across several domains.
- ☁️ **One-click deploy** — Cloudflare Pages with automatic builds on every push.

## Tech Stack

`Astro` · `AstroWind` · `Sveltia CMS` · `Tailwind CSS` · `TypeScript` · `Cloudflare Pages` · `Jamstack`

## Quick Start

**Requirements:** Node.js 18+ and npm.

```bash
# 1. Clone
git clone https://github.com/KomeStudio/WebCore.git
cd WebCore

# 2. Install
npm install

# 3. Run locally → http://localhost:4321
npm run dev

# 4. Build for production → ./dist
npm run build

# 5. Preview the production build
npm run preview
```

## Content Management (Sveltia CMS)

1. Open `/admin` on your site (local or deployed).
2. Sign in with your Git provider.
3. Edit pages, posts and settings — changes are committed to the repository and trigger a new deploy.

Collections and fields are defined in the CMS config file (`/public/admin/config.yml`).

## Deploy to Cloudflare Pages

| Setting | Value |
| --- | --- |
| Framework preset | Astro |
| Build command | `npm run build` |
| Output directory | `dist` |
| Node version | 18 or newer |

Connect the repository, set your custom domain (e.g. `komestudio.com`, `kome.top`), and every push to `master` deploys automatically.

## SEO Checklist for Each Site

- [ ] Set the site URL, title and description in the site config.
- [ ] Add a unique `title` and `description` to every page and post.
- [ ] Provide an Open Graph image (1200×630).
- [ ] Submit `sitemap-index.xml` to Google Search Console and Bing Webmaster Tools.
- [ ] Verify canonical URLs point to the primary domain.

## Contributing

Issues and pull requests are welcome. For bugs or feature requests, please [open an issue](https://github.com/KomeStudio/WebCore/issues).

## Credits

Built on [AstroWind](https://github.com/onwidget/astrowind), [Astro](https://astro.build), [Tailwind CSS](https://tailwindcss.com) and [Sveltia CMS](https://github.com/sveltia/sveltia-cms).

## License

Released under the **GPL-3.0** license. See [LICENSE](./LICENSE) for details.

---

### 🇻🇳 Tiếng Việt

**Kome WebCore** là bộ mã nguồn website dùng chung (Astro + AstroWind + Sveltia CMS + Tailwind CSS) cho [komestudio.com](https://komestudio.com) và [kome.top](https://kome.top). Website tĩnh tốc độ cao, chuẩn SEO, quản lý nội dung bằng CMS trực quan và triển khai miễn phí trên Cloudflare Pages.

<sub>**Keywords:** Kome Studio, komestudio.com, kome.top, Astro template, AstroWind, Sveltia CMS, headless CMS, Jamstack, static site generator, Tailwind CSS, TypeScript, Cloudflare Pages, SEO website template, game studio website.</sub>
