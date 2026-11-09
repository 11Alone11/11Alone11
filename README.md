<div align="center">

[English](README.en.md) · **Русский**

# Антон Стасюк

**Frontend-разработчик** · React / Vue · TypeScript

Минск, Беларусь · удалённо или гибрид · открыт к предложениям

[![Telegram](https://img.shields.io/badge/Telegram-@AntonStasiuk-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/AntonStasiuk)
[![Email](https://img.shields.io/badge/Email-anton.stasyuk.0@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:anton.stasyuk.0@gmail.com)

</div>

## О себе

Frontend-разработчик с 3+ годами коммерческого опыта. Разрабатываю интерфейсы для продуктов,
где важны скорость, SEO и сложные пользовательские сценарии: интернет-магазины, маркетплейсы
объявлений, картографические сервисы, PWA и Telegram Mini Apps.

Работаю в двух экосистемах — React (Redux Toolkit, TanStack Query, React Hook Form) и Vue/Nuxt
(Pinia, Composition API, SSR/SSG). Умею довести продукт до продакшена целиком: от вёрстки
по макетам Figma до архитектуры компонентов, интеграции с API и метрик Core Web Vitals.

Отдельный интерес — открытый исходный код: сообщаю об ошибках в Vue и Nuxt, предлагаю исправления
и помогаю с документацией на русском и английском языках.

## Стек

**Языки и фреймворки**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue 3](https://img.shields.io/badge/Vue%203-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxtdotjs&logoColor=white)

**Состояние и данные**

![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=flat-square&logoColor=black)
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=flat-square)

**Интерфейс**

![MUI](https://img.shields.io/badge/MUI-007FFF?style=flat-square&logo=mui&logoColor=white)
![Mantine](https://img.shields.io/badge/Mantine-339AF0?style=flat-square)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white)

**Инструменты**

![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

## Проекты

### IT-подразделение МВД — картографическое веб-приложение

`ноябрь 2025 — октябрь 2026` · React · TypeScript · Redux Toolkit · TanStack Query · MUI · Mantine · MapLibre GL JS

- Разработал картографический модуль на MapLibre GL JS с WebGL: плавное отображение и кластеризация
  50 000+ объектов на карте.
- Доработал библиотеку Terra Draw для рисования, редактирования и управления геометрическими
  объектами на карте.
- Перевёл работу с серверными данными в ключевых модулях на TanStack Query: кеширование,
  инвалидация запросов и optimistic updates.
- Обновил React, Vite, картографические библиотеки и UI-киты; сократил production-сборку
  с 45 до 10 секунд.
- Реализовал отображение и обработку 100 000+ записей в списках и таблицах: пагинация,
  виртуализация и бесконечная прокрутка.
- Собрал многошаговые формы со сложной валидацией и зависимыми полями на React Hook Form.
- Разработал набор переиспользуемых UI-компонентов на MUI и Mantine для унификации интерфейсов.

### Бонусторг — платформа объявлений об автомобилях

`ноябрь 2024 — октябрь 2025` · Vue 3 · Nuxt · TypeScript · Pinia · Vite

- Перевёл проект с JavaScript на TypeScript и мигрировал с Nuxt 3 на Nuxt 4, вынеся бизнес-логику
  в composables и модули Pinia.
- Спроектировал 5 новых разделов и доработал 7 существующих, включая многошаговую форму подачи
  объявления с сохранением черновика между этапами.
- Реализовал параметрическую фильтрацию и поиск автомобилей с синхронизацией состояния в URL.
- Сократил LCP с 2,4 до 1,5 с: оптимизировал загрузку изображений первого экрана и кэширование
  статических ресурсов; устранил сдвиги вёрстки (CLS).
- Закрыл XSS-уязвимость: добавил проверку и санитизацию пользовательского ввода в местах,
  где данные попадают в приложение.
- Разработал 30+ переиспользуемых UI-компонентов и исправил специфичные для Safari на iOS и macOS
  баги отображения. Проводил code review и технические собеседования.

### БИРЖЕВИК — PWA с ценами в реальном времени

`март — октябрь 2024` · [beerzhevik.ru](https://beerzhevik.ru) · Vue 3 · Nuxt 3 · TypeScript · WebSocket · Chart.js

Платформа для бара: гости и персонал видят актуальные цены на позиции меню, которые меняются
в зависимости от спроса.

- Обновление меню и цен в реальном времени через WebSocket — без перезагрузки страницы.
- Авторизация на JWT и сценарии для трёх ролей: администратор, официант, посетитель.
- Адаптивный интерфейс под смартфоны и ТВ-экраны с разными способами взаимодействия.
- Визуализация аналитики на Chart.js.
- Согласовывал с заказчиком требования и изменения фронтенд-архитектуры.

### veloman.by — интернет-магазин велосипедов

`ноябрь 2023 — март 2024` · [veloman.by](https://veloman.by) · Vue 3 · Nuxt 3 (SSR) · Pinia · Sass

Полный редизайн магазина. Единственный frontend-разработчик на проекте: от макетов Figma
до production-сборки.

- Фронтенд с нуля на Nuxt 3 SSR: каталог, карточка товара, корзина, избранное, отзывы.
- Корзина и избранное на Pinia с синхронизацией в localStorage и cookies с учётом SSR.
- Pixel-perfect адаптивная вёрстка по макетам Figma на Sass.
- SEO: динамические метатеги, семантическая разметка и Schema.org/JSON-LD для товаров и отзывов.
- Code splitting и ленивая загрузка медиа для быстрой загрузки страниц.

### ProEdu — Telegram Mini App

`май — август 2023` · [@pro_edu_official_bot](https://t.me/pro_edu_official_bot) · JavaScript · Telegram WebApps API · Sass

- Встроил веб-приложение в экосистему Telegram через Telegram WebApps API.
- Реализовал систему заданий, квестов и наград для вовлечения пользователей.
- Свёрстал интерфейс под ограничения WebView на iOS, Android и Desktop.

### Спецтехника — лендинг аренды спецтехники

`ноябрь 2026` · [код](https://github.com/11Alone11/Gruzoperevozki_ai) · [сайт](https://11alone11.github.io/Gruzoperevozki_ai/)

Одностраничный сайт на GitHub Pages без сервера: разметка, стили и JS в одном файле.

- Content-Security-Policy с хешами, автоматически рассчитываемыми на сборке.
- JSON-LD, sitemap.xml, webmanifest, страница 404 — базовая SEO-обвязка без фреймворка.

## Open source

Участвую в жизни экосистемы Vue и Nuxt: сообщаю об ошибках, предлагаю исправления и помогаю
с документацией на русском и английском языках.

- [vuejs/docs](https://github.com/vuejs/docs), [vuejs-translations/docs-ru](https://github.com/vuejs-translations/docs-ru) — документация Vue 3
- [vuejs/pinia](https://github.com/vuejs/pinia), [vuejs/router](https://github.com/vuejs/router) — управление состоянием и роутинг
- [nuxt/nuxt](https://github.com/nuxt/nuxt) — фреймворк и его документация

## Образование

**БГУИР**, Минск — Автоматизированные системы обработки информации (ФИТУ), 2025
