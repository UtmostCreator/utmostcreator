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
  <a href="https://stackoverflow.com/users/6901693/utmost-creator">
    <img src="https://img.shields.io/badge/Stack_Overflow-Answers-F58025?style=for-the-badge&logo=stackoverflow&logoColor=white" alt="Stack Overflow profile" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Experience-10%2B_years-1F6FEB?style=flat-square" alt="10+ years of experience" />
  <img src="https://img.shields.io/badge/Focus-Commerce_·_Reliability_·_Integrations-0E7490?style=flat-square" alt="Commerce, reliability and integrations" />
  <img src="https://img.shields.io/badge/Domains-Commerce_·_Travel_·_EdTech_·_IoT-0F172A?style=flat-square" alt="Commerce, travel, EdTech, IoT" />
  <img src="https://img.shields.io/badge/English-C2-15803D?style=flat-square" alt="English C2" />
</p>

> I build and maintain revenue-critical systems: checkout, pricing, booking and finance integrations. I take hard production problems through root-cause investigation, remediation and verification, and I make established codebases safer to change through testing, tooling and modernisation.
>
> Currently at **Rabbie's**, working on a Laravel/Statamic CMS, a Nuxt storefront, checkout and the integration with the company's booking system.

## Impact

| Area | Evidence |
| --- | --- |
| **Transactional correctness** | Investigated cross-system pricing and currency discrepancies and improved end-to-end pricing consistency through checkout |
| **Booking integrity** | Delivered the website side of hotel-and-tour packages: live availability, pricing validation and safeguards for concurrent bookings |
| **Production reliability** | Diagnosed intermittent production and integration failures and improved error handling, diagnostics and resilience |
| **Safe change** | Made the CMS test suite substantially faster and lighter on memory; shipped upgrades with rollback plans and verification checklists |
| **Content localisation** | Took regional spelling localisation from proof of concept to production across the CMS and its content APIs |
| **Finance integration** | Built the Moodle/Totara-NetSuite integration behind HFL Education's award-winning learning platform |
| **Platform modernisation** | Led the PHP 5.4 → 7.4 migration, schema redesign and query optimisation on the MaxTracking logistics platform |

## Selected Work

### Rabbie's - Senior Web Developer, January 2026 to present

Full-stack engineering on a **Laravel / Statamic CMS, Nuxt / Vue storefront, checkout and shared Vue component library** for a [travel and tour operator](https://rabbies.com/), integrated with the company's booking system, Stripe and third-party services.

**Investigation and reliability**

- **Pricing integrity:** Led root-cause analysis of pricing and currency inconsistencies spanning the storefront, CMS, checkout and booking system. I added structured diagnostics, established which system each discrepancy came from, fixed the website side with regression tests, and wrote the QA scenarios used for verification.
- **Production diagnostics:** Investigated complex production and integration failures, identifying root causes and delivering verified improvements to error handling, diagnostics and resilience, on both sides of the booking-system integration.
- **Publishing reliability:** Improved content-publishing reliability and cache consistency across regional websites, supported by regression tests.

**Commerce, content and SEO**

- **Hotel-and-tour packages:** Integrated room-availability, pricing and capacity APIs with typed DTOs, immutable dates, validation and safeguards for concurrent bookings.
- **Checkout and integrations:** Payment-processing feedback, marketing-consent options and simpler add-on selection; Zoho forms with secure embedding, consent-gated third-party scripts, Trustpilot reviews and analytics tagging.
- **Localisation and versioning:** Scoped per-region spelling localisation (e.g. UK → US) with stakeholders and took it from proof of concept to production across GraphQL and REST content, with documentation for development, QA and editors. Added revision history with retention safeguards that protect published content.
- **SEO, search and frontend:** Sitemaps per currency and locale, same-region search results, clean pagination URLs and structured data; navigation redesign in the shared Vue 3 component library, responsive images and hydration fixes.

**Delivery quality and team enablement**

- Optimised PHPUnit test execution and memory usage through framework lifecycle improvements and stronger test isolation, making the suite **substantially faster and stable within a standard memory limit**.
- Resolved CI reliability issues and strengthened dependency validation and security maintenance; delivered upgrades with rollback plans and verification checklists, and triaged error monitoring into prioritised fixes.
- Created a shared Bruno API collection and documentation for the team's interconnected services, added stable Cypress selectors to key journeys, and wrote deployment steps and QA scenarios. I clarified acceptance criteria with product and split cross-team issues into scoped follow-ups.

**Stack:** PHP 8.3, Laravel, Statamic, GraphQL, REST, MariaDB, Nuxt, Vue 3, TypeScript, Algolia, Tailwind CSS, Stripe, Docker, PHPUnit, Vitest, Cypress, GitHub Actions

### Accipio - enterprise learning and finance integration

- Architected **Moodle/Totara-NetSuite synchronisation** covering organisations, users, invoices, products and subscriptions, replacing error-prone manual workflows with automated data exchange.
- Delivered integration and commerce workflows for **HFL Education** as part of Accipio's [award-winning Totara implementation](https://www.accipio.com/accipio-wins-totara-award-for-best-use-of-integrations-2024/). The platform [generated seven-figure revenue within its first 10 months](https://totara.com/us/customer-stories/hfl-education-generates-seven-figures-of-revenue-within-first-10-months/), sold 30,000 licences and synchronised 34,000+ organisations with NetSuite.
- Developed reusable mapping, commerce/search and multi-grader capabilities that reduced administrative work and improved data consistency.

**Stack:** Totara, Moodle, NetSuite, SuiteQL, PHP, REST APIs, jQuery

### MaxTracking - legacy modernisation

- Migrated a live logistics platform from **PHP 5.4 to 7.4** without disrupting operations, introducing Symfony-based internal framework patterns.
- Redesigned schemas, optimised queries and strengthened CLI and cron-driven workflows.
- Ran and maintained bulk email workflows that processed 500k+ transactional and marketing emails, including invoices and campaign communications.

**Stack:** PHP, Symfony, MySQL, REST APIs, Bootstrap, cPanel

### BYND Smart Home - frontend platform migration

- Migrated an IoT control SPA from **Aurelia to Vue 3** and built real-time device interactions over MQTT and Socket.IO.
- Contributed to a Storybook-led component system that reduced UI bugs by 40%, and developed a dynamic floor-plan editor.

**Stack:** Vue, Node.js, MQTT, Socket.IO, FAST UI, Storybook, FeathersJS, Webpack

### Personal projects

app-configs is public; the others are private and in active development.

- **[app-configs](https://github.com/UtmostCreator/app-configs):** reproducible developer environments across macOS and Linux using Nix, Home Manager, chezmoi and mise, with automated provisioning, configuration validation, guarded updates, snapshots and recovery workflows. _Nix, Bash._
- **Glyphbrace:** multi-provider AI development tooling (Claude Code, Codex, GitHub Copilot) that installs agents, skills and project guidance, preserving user modifications through conflict-aware, recoverable updates. _Go._
- **AI Monitoring:** provider-neutral telemetry and evaluation system for AI coding agents (Claude Code, GitHub Copilot, OpenCode). Durable PostgreSQL evidence pipeline with JSON Schema validation, idempotent ingestion, quarantine and transactional outbox; OpenTelemetry/Phoenix tracing; Python evaluation plane over promptfoo and Inspect. _TypeScript, PostgreSQL, Python, OpenTelemetry._
- **RestSift:** repository-aware CLI for AI coding agents and reviewers: scoped search, context packing, guarded edits with rollback, test selection and evidence-based verification. _Bash, Node.js._
- **KitPact:** Go library for safely installing, updating and uninstalling files in existing projects, preserving user edits, detecting conflicts and recovering from crashes. _Go._
- **Advanced Gym:** offline-first Kotlin Multiplatform strength-training app with shared Compose UI; Android first, iOS host in place. _Kotlin, Compose Multiplatform._

Earlier: a solo Unreal Engine 4 multiplayer shooter with server-authoritative health, weapons, progression and leaderboards in C++ and Blueprints.

## Core Stack

| Area         | Skills                                                                                                              |
| ------------ | ------------------------------------------------------------------------------------------------------------------- |
| **Backend**  | PHP 8, Laravel, Symfony, Yii2, Statamic, REST APIs, GraphQL, MySQL/MariaDB, SQL optimisation                        |
| **Frontend** | JavaScript/TypeScript, Vue 2/3, Nuxt, Tailwind CSS, Algolia, HTML/CSS, Storybook; Angular, Aurelia, jQuery (legacy) |
| **Platform** | Git, GitHub Actions, Docker, Linux, Nix, Apache, CI/CD, scheduled jobs and queues                                   |
| **Quality**  | PHPUnit, Vitest, Cypress, Selenium, Postman/Bruno, JMeter, SonarQube, integration and E2E testing                   |
| **Security** | OWASP, CSP, XSS/CSRF/SQL-injection mitigation, dependency vulnerability remediation                                 |

## Education and Certifications

- Master's degree (MSc) in Software Engineering, with honours
- BA in Germanic Languages and English Translation
- QATestLab Certified Test Engineer
- British Council English certification at C2 level
