<div align="center">

**English** · [Русский](README.md)

# Anton Stasiuk

**Frontend Developer** · React / Vue · TypeScript

Minsk, Belarus · remote or hybrid · open to opportunities

[![Telegram](https://img.shields.io/badge/Telegram-@AntonStasiuk-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/AntonStasiuk)
[![Email](https://img.shields.io/badge/Email-anton.stasyuk.0@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:anton.stasyuk.0@gmail.com)

</div>

## About

Frontend developer with 3+ years of commercial experience. I build interfaces for products where
speed, SEO and complex user flows matter: e-commerce, classifieds marketplaces, mapping services,
PWAs and Telegram Mini Apps.

I work across two ecosystems — React (Redux Toolkit, TanStack Query, React Hook Form) and Vue/Nuxt
(Pinia, Composition API, SSR/SSG). I take products to production end to end: from Figma-accurate
markup to component architecture, API integration and Core Web Vitals.

I also contribute to open source: I report bugs in Vue and Nuxt, propose fixes and help with
documentation in Russian and English.

## Stack

**Languages and frameworks**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue 3](https://img.shields.io/badge/Vue%203-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxtdotjs&logoColor=white)

**State and data**

![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=flat-square&logoColor=black)
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=flat-square)

**Interface**

![MUI](https://img.shields.io/badge/MUI-007FFF?style=flat-square&logo=mui&logoColor=white)
![Mantine](https://img.shields.io/badge/Mantine-339AF0?style=flat-square)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white)

**Tooling**

![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

## Projects

### Ministry of Internal Affairs, IT unit — mapping web application

`November 2025 — October 2026` · React · TypeScript · Redux Toolkit · TanStack Query · MUI · Mantine · MapLibre GL JS

- Built a MapLibre GL JS (WebGL) mapping module that renders and clusters 50,000+ objects smoothly.
- Extended the Terra Draw library for drawing, editing and managing geometric objects on the map.
- Moved server data handling in key modules to TanStack Query, with caching, query invalidation
  and optimistic updates.
- Upgraded React, Vite, mapping libraries and UI kits; cut production build time from 45 s to 10 s.
- Rendered and handled 100,000+ records in lists and tables with pagination, virtualisation
  and infinite scroll.
- Built multi-step forms with complex validation and dependent fields on React Hook Form.
- Created a reusable UI component set on MUI and Mantine to unify the application's interfaces.

### Bonustorg — automotive classifieds platform

`November 2024 — October 2025` · Vue 3 · Nuxt · TypeScript · Pinia · Vite

- Migrated the project from JavaScript to TypeScript and from Nuxt 3 to Nuxt 4, moving business
  logic into composables and Pinia modules.
- Designed 5 new sections and reworked 7 existing ones, including a multi-step listing form that
  keeps drafts between steps.
- Built parametric filtering and car search with state synced to the URL.
- Improved LCP from 2.4 s to 1.5 s by optimising above-the-fold images and static asset caching;
  eliminated layout shifts (CLS).
- Fixed an XSS vulnerability by validating and sanitising user input where data enters the app.
- Built 30+ reusable UI components and fixed Safari-specific rendering issues on iOS and macOS.
  Ran code reviews and technical interviews.

### Beerzhevik — real-time pricing PWA

`March — October 2024` · [beerzhevik.ru](https://beerzhevik.ru) · Vue 3 · Nuxt 3 · TypeScript · WebSocket · Chart.js

A bar platform: guests and staff see up-to-date menu prices that change with demand.

- Real-time menu and price updates over WebSocket, with no page reloads.
- JWT authentication and flows for three roles: administrator, waiter and guest.
- Responsive UI for phones and TV screens, adapted to different interaction models.
- Analytics visualisation with Chart.js.
- Agreed requirements and frontend architecture changes with the client.

### veloman.by — bike e-commerce store

`November 2023 — March 2024` · [veloman.by](https://veloman.by) · Vue 3 · Nuxt 3 (SSR) · Pinia · Sass

A full store redesign as the only frontend developer on the project: from Figma files to the
production build.

- Frontend built from scratch on Nuxt 3 SSR: catalog, product page, cart, wishlist, reviews.
- Cart and wishlist state in Pinia, synced to localStorage and cookies with SSR in mind.
- Pixel-perfect responsive markup from Figma, in Sass.
- SEO: dynamic meta tags, semantic markup and Schema.org/JSON-LD for products and reviews.
- Code splitting and lazy-loaded media for fast page loads.

### ProEdu — Telegram Mini App

`May — August 2023` · [@pro_edu_official_bot](https://t.me/pro_edu_official_bot) · JavaScript · Telegram WebApps API · Sass

- Embedded the web app into the Telegram ecosystem via the Telegram WebApps API.
- Implemented a system of tasks, quests and rewards to drive user engagement.
- Built the UI around WebView constraints on iOS, Android and Desktop.

### Construction equipment rental landing

`November 2026` · [code](https://github.com/11Alone11/Gruzoperevozki_ai) · [live](https://11alone11.github.io/Gruzoperevozki_ai/)

A single-page site on GitHub Pages with no server: markup, styles and JS in a single file.

- Content-Security-Policy with hashes generated at build time.
- JSON-LD, sitemap.xml, web manifest and a 404 page — basic SEO plumbing without a framework.

## Open source

I contribute to the Vue and Nuxt ecosystem: reporting bugs, proposing fixes and helping with
documentation in Russian and English.

- [vuejs/docs](https://github.com/vuejs/docs), [vuejs-translations/docs-ru](https://github.com/vuejs-translations/docs-ru) — Vue 3 documentation
- [vuejs/pinia](https://github.com/vuejs/pinia), [vuejs/router](https://github.com/vuejs/router) — state management and routing
- [nuxt/nuxt](https://github.com/nuxt/nuxt) — the framework and its documentation

## Education

**BSUIR**, Minsk — Automated Information Processing Systems (FITU), 2025
