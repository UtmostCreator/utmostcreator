<h1 align="center">Roman Zakhriapa</h1>

<p align="center">
  <strong>Senior Full-Stack &amp; Platform Engineer</strong><br />
  PHP · Laravel/Symfony · Vue/Nuxt · SQL · APIs &amp; Integrations
</p>

<p align="center">
  Edinburgh, UK | UK work authorisation | No sponsorship required
</p>

<p align="center">
  <a href="https://drive.google.com/file/d/1hOsicesm-gh7LihDOrLMGLp0Y2CkUoMX">
    <img src="https://img.shields.io/badge/CV-Download-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Download CV" />
  </a>
  <a href="https://www.linkedin.com/in/utmost-creator/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Experience-10%2B_years-1F6FEB?style=flat-square" alt="10+ years of experience" />
  <img src="https://img.shields.io/badge/Focus-Modernisation_%26_integrations-0E7490?style=flat-square" alt="Modernisation and integrations" />
  <img src="https://img.shields.io/badge/Domains-Commerce_·_Travel_·_EdTech_·_IoT-0F172A?style=flat-square" alt="Commerce, travel, EdTech, IoT" />
  <img src="https://img.shields.io/badge/English-C2-15803D?style=flat-square" alt="English C2" />
</p>

> I modernise production systems, build business-critical integrations, and turn complex operational workflows into maintainable products.
>
> Currently building booking, checkout, integrations, and platform functionality at **Rabbie's**.

## Impact

| Area                        | Evidence                                                                                                                                                                                                                                                                                                                                                                                  |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Production commerce**     | Delivered a major Rabbie’s checkout pricing and currency reliability improvement across locales and currencies, resolving high-impact session-state and pricing inconsistencies and ensuring correct regional pricing throughout the customer journey. Building booking, checkout, and accommodation-availability flows on Rabbie's transactional travel                                  |
| **Revenue / commerce**      | Built Moodle/Totara-NetSuite synchronisation and billing workflows for HFL Education; the [award-winning Totara implementation](https://www.accipio.com/accipio-wins-totara-award-for-best-use-of-integrations-2024/) generated [seven-figure revenue within its first 10 months](https://www.linkedin.com/posts/totara_customerstory-education-totara-activity-7221488120469274624-fxeD) |
| **Platform modernisation**  | Led the PHP 5.4 → 7.4 migration, schema redesign, and query optimisation on the MaxTracking logistics platform                                                                                                                                                                                                                                                                            |
| **Frontend / IoT**          | Migrated BYND's smart-home SPA from Aurelia to Vue 3 with real-time MQTT and Socket.IO device control                                                                                                                                                                                                                                                                                     |
| **Product engineering**     | Building Advanced Gym, an offline-first Kotlin Multiplatform training app with shared Compose UI for Android and iOS                                                                                                                                                                                                                                                                      |
| **Developer tooling · WIP** | Building restsift, repository-aware CLI tooling for code search, context generation, Git inspection, verification, testing and repeatable AI-assisted development                                                                                                                                                                                                                         |

## Selected Work

### Rabbie's - Senior Web Developer, January 2026 to present

Production engineering across a **Laravel 12 / Statamic 5 backend, Nuxt 4 / Vue 3 storefront, and shared Vue component library**, delivering booking, checkout, content, integrations, and reusable UI for a [travel and tour operator](https://rabbies.com/).

- Built and hardened **direct-package room-availability APIs** against the Internal booking system - typed DTOs, immutable date handling, capacity and pricing validation, and diagnostic logging across accommodation journeys.
- Implemented checkout currency and session-state handling across Nuxt, CMS, and checkout flows: persistent currency/session state, internal API-driven currency switching, GeoIP-based default currency selection, and consistent propagation of pricing context between systems.
- Reworked **XML/HTML sitemap generation** across currencies and locales, resolving 500 errors and long load times on the HTML sitemap, and wiring robots.txt
- Delivered **content-platform capability in Statamic**: entry revisions with retention rules for tours, pages, and search results, plus word replacement localisation across GraphQL and REST responses, and cache-invalidation correctness across collections.
- Worked on **Zoho Web-to-Lead** enquiry forms with dedicated CSP middleware for secure iframe embedding.
- Contributed to **shared Vue 3 component-library** development within the engineering team, including mega-navigation, banners, Trustpilot reviews, Algolia site search and indexing, hydration fixes, and PHPUnit/Vitest test coverage.

**Stack:** PHP 8.3, Laravel 11-12, Statamic 5-6, GraphQL, MariaDB, Nuxt 4, Vue 3, Algolia, Tailwind CSS, Stripe, Docker, PHPUnit, Vitest

### Accipio - enterprise learning and finance integration

- Architected **Moodle/Totara-NetSuite synchronisation** across organisations, users, invoices, products, and subscriptions, replacing error-prone manual workflows with automated data exchange.
- Built integration and commerce workflows for **HFL Education** as part of Accipio's [award-winning Totara implementation](https://www.accipio.com/accipio-wins-totara-award-for-best-use-of-integrations-2024/); the resulting platform [generated seven-figure revenue within its first 10 months](https://totara.com/us/customer-stories/hfl-education-generates-seven-figures-of-revenue-within-first-10-months/), sold 30,000 licences, and synchronised 34,000+ organisations with NetSuite.
- Developed reusable mapping, commerce/search, and multi-grader capabilities that reduced administrative work and improved data consistency across learning and commerce workflows.

**Stack:** Totara, Moodle, NetSuite, SuiteQL, PHP, REST APIs, jQuery

### MaxTracking - legacy modernisation

- Migrated a live logistics platform from **PHP 5.4 to 7.4** without disrupting operations, introducing Symfony-based internal framework patterns.
- Redesigned schemas and optimised queries, and strengthened CLI and cron-driven workflows.
- Built and maintained bulk email workflows that processed 500k+ transactional and marketing emails, including invoices and campaign communications.

**Stack:** PHP, Symfony, MySQL, REST APIs, Bootstrap, cPanel

### BYND Smart Home - frontend platform migration

- Migrated an IoT control SPA from **Aurelia to Vue 3** and built real-time device interactions over MQTT and Socket.IO.
- Contributed to a Storybook-led component system that reduced UI bugs by 40%, and developed a dynamic floor-plan editor.

**Stack:** Vue, Node.js, MQTT, Socket.IO, FAST UI, Storybook, FeathersJS, Webpack

### Advanced Gym - Kotlin Multiplatform (in active development)

Personal product for structured strength training with offline-first workout planning and logging, exercise substitution, set/RIR tracking, and progression workflows. Built with an `:app` + `:shared` Kotlin Multiplatform architecture and shared Compose UI; Android is the current primary target with an iOS host already in place.

**Stack:** Kotlin, Compose Multiplatform, KMP, Coroutines/Flow, Gradle, Android/iOS

Earlier: a solo Unreal Engine 4 multiplayer shooter with server-authoritative health, weapons, progression, and leaderboard systems in C++ and Blueprints.

## Public Proof

- **[UtmostCreator/app-configs](https://github.com/UtmostCreator/app-configs)** - reproducible development environment for macOS, Linux, and NixOS via chezmoi, mise, Nix/Home Manager, and Lefthook.
- **[UtmostCreator/github-actions](https://github.com/UtmostCreator/github-actions)** - reusable GitHub Actions workflows and CI/CD patterns.
- **[HumHub](https://github.com/humhub/humhub)** - open-source contributions to the HumHub platform and related repositories.
- **[Stack Overflow](https://stackoverflow.com/users/6901693/utmost-creator)** - technical answer history.
- AI engineering project - coming soon - agent-oriented developer tooling for governed AI-assisted software engineering, multi-provider workflows, structured handoffs, validation, and repeatable development processes.

UtmostCreator/restsift - coming soon - repository-aware CLI tooling for code search, context generation, Git inspection, verification, testing, and repeatable AI-assisted development.

## Core Stack

| Area         | Skills                                                                                                   |
| ------------ | -------------------------------------------------------------------------------------------------------- |
| **Backend**  | PHP 8, Laravel, Symfony, Yii2, Statamic, REST APIs, GraphQL, MySQL/MariaDB, SQL optimisation             |
| **Frontend** | JavaScript, Vue 2/3, Nuxt, Tailwind CSS, Algolia, HTML/CSS, Storybook; Angular, Aurelia, jQuery (legacy) |
| **Platform** | Git, GitHub Actions, Docker, Linux, Apache, CI/CD                                                        |
| **Quality**  | PHPUnit, Vitest, Cypress, Selenium, Postman, JMeter, SonarQube, integration and E2E testing              |
| **Security** | OWASP, CSP, XSS/CSRF/SQL-injection mitigation, dependency vulnerability remediation                      |

## Education and Certifications

- Master's degree (MSc) in Software Engineering, with honours
- BA in Germanic Languages and English Translation
- QATestLab Certified Test Engineer
- British Council English certification at C2 level
