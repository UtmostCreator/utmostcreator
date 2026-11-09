<h1 align="center">Roman Zakhriapa</h1>

<p align="center">
  <strong>Senior Full-Stack Engineer</strong><br />
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
  <img src="https://img.shields.io/badge/Experience-10%2B_years-1F6FEB?style=flat-square" alt="10+ years of professional experience" />
  <img src="https://img.shields.io/badge/Focus-Commerce_·_Reliability_·_Integrations-0E7490?style=flat-square" alt="Commerce, reliability and integrations" />
  <img src="https://img.shields.io/badge/Domains-Commerce_·_Travel_·_EdTech_·_IoT-0F172A?style=flat-square" alt="Commerce, travel, EdTech, IoT" />
  <img src="https://img.shields.io/badge/English-C2-15803D?style=flat-square" alt="English C2" />
</p>

> I build and maintain revenue-critical systems: checkout, pricing, booking and finance integrations. I take hard production problems through root-cause investigation, remediation and verification, and I make established codebases safer to change through testing, tooling and modernisation.
>
> Currently at **Rabbie's**, working on a Laravel/Statamic CMS, a Nuxt storefront, checkout and the integration with the company's booking system.
>
> Freelance: 100% Job Success and Top Rated status on Upwork. Recommendations from MaxTracking and BYND clients on [LinkedIn](https://www.linkedin.com/in/utmost-creator/).

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

- **Pricing integrity:** Led root-cause analysis of cross-system pricing and currency inconsistencies; added diagnostics, traced each discrepancy's source, fixed the website side with regression tests and wrote QA scenarios.
- **Production diagnostics:** Found root causes of complex production and integration failures and delivered verified error-handling, diagnostics and resilience fixes on both sides of the booking integration.
- **Publishing reliability:** Improved content-publishing reliability and cache consistency across regional websites, supported by regression tests.

**Commerce, content and SEO**

- **Hotel-and-tour packages:** Integrated room-availability, pricing and capacity APIs with typed DTOs, immutable dates, validation and safeguards for concurrent bookings.
- **Checkout and integrations:** Fixed currency and step-order defects; payment feedback, marketing consent and simpler add-ons; secure Zoho form embeds, consent-gated scripts, Trustpilot reviews and analytics tags.
- **Checkout consistency:** Kept prices, currency and booking country stable from the first checkout step to confirmation, with regression tests.
  - Added tests ensuring each checkout session starts clean, with no state carried over between sessions.
  - Locked the pricing region for the whole checkout so IP or session drift cannot change the booking country, with regression tests.
  - Applied exchange rates consistently to tours, attractions and supplements on the confirmation page, and fed analytics from the booking system's net price.
- **Localisation and versioning:** Designed the spelling-localisation strategy and schema, scoped UK → US variants with stakeholders and shipped it from proof of concept to production for UK, US and EU sites (GraphQL, REST).
  - Added revision history with retention safeguards that protect published content.
  - Editor controls to sync or de-sync localised entries across several content types, plus per-region localisable image metadata.
  - Authored editor and developer guides for the localisation feature, with worked examples.
- **API documentation and contracts:** Evaluated and selected Laravel Scramble for OpenAPI 3.1 documentation; proposed API endpoints and request contracts for cross-system integrations.
- **SEO, search and frontend:** Per-currency and per-locale sitemaps, same-region search, clean pagination URLs and structured data; shared Vue 3 navigation redesign, responsive images and hydration fixes.
- **Hydration and region safety:** Fixed SSR hydration mismatches in the Nuxt storefront with a client-only boundary for widgets; added region validation that fails fast instead of saving bad state.

**Delivery quality and team enablement**

- Optimised PHPUnit test execution and memory usage through framework lifecycle improvements and stronger test isolation, making the suite **faster and leaner (415 MB → 189 MB peak memory)**.
- Improved locale-aware cache invalidation, with regression tests.
- Used static-analysis findings to reduce method complexity across checkout and services.
- Hardened CI to run on every PR and push to main and fail loudly on a missing secret; strengthened dependency validation and security maintenance.
- Delivered upgrades with rollback plans and verification checklists, and triaged error monitoring into prioritised fixes.
- Created a shared Bruno API collection and docs for interconnected services, stable Cypress selectors on key journeys, deployment steps and QA scenarios; clarified acceptance criteria and scoped cross-team follow-ups.
- **Authored test and QA documentation:**
  - End-to-end test coverage audit with a prioritised gap list covering checkout journeys, mobile booking and error states.
  - Test-performance profiling runbook with a memory budget and best-practice rules.

**Stack:** PHP 8.3, Laravel, Statamic, GraphQL, REST, MariaDB, Nuxt, Vue 3, Algolia, Tailwind CSS, Stripe, Docker, PHPUnit, Vitest, Cypress, GitHub Actions, OpenAPI (Scramble)

### Accipio - enterprise learning and finance integration

- Architected **two-way Moodle/Totara-NetSuite REST synchronisation** covering organisational, user, product, subscription and financial data, replacing manual workflows with automated data exchange.
- Improved **data reconciliation** between NetSuite and Totara, resolving inconsistencies across invoices, orders and customer records.
- Built reusable **field mapping**, validated setup workflows and data bundles for API sync, reducing manual administration and errors.
- Contributed to Accipio's [award-winning HFL Education implementation](https://www.accipio.com/accipio-wins-totara-award-for-best-use-of-integrations-2024/) (2024 Totara Award for Best Use of Integrations). The platform [publicly reported seven-figure revenue in its first 10 months](https://totara.com/us/customer-stories/hfl-education-generates-seven-figures-of-revenue-within-first-10-months/), 30,000 licences sold and 34,000+ organisations synced with NetSuite.
- Developed course and event **catalogue search and filtering**, including product views, session and ticket filters and catalogue tags.
- Designed **modular multi-grader allocation** with configurable assessor and moderator roles, supporting manual and automated assignment; contributed to automated grade resolution.

**Stack:** PHP, Moodle, Totara, NetSuite, SuiteQL, MySQL, REST APIs, JWT, jQuery

### MaxTracking - legacy modernisation

- Architected an in-house **Laravel-inspired PHP MVC framework** using Symfony components (routing, database abstraction, prepared queries, validation), applying the MVC, Singleton, Command, ActiveRecord and Iterator patterns.
- Led a live **PHP 5.4 to 7.4** migration without disrupting operations, with PSR-12 standards, tagged releases and changelogs.
- Delivered invoicing end to end and redesigned schemas, optimised queries and strengthened CLI and cron-driven workflows.
- Introduced **PHPStan** static analysis and **Deptrac** architectural dependency checks to identify defects and unwanted coupling earlier, improving maintainability and development quality.
- Redesigned bulk email campaign processing so campaigns recover after interruptions.
  - **2023-26:** Runs resume from the last sent recipient via a per-campaign progress record, report completion and send only within a configured time window.
  - **2023-26:** Extended the Symfony Console campaign command with SMTP validation on account switch and a nohup wrapper for background runs.

<details>
<summary>MaxTracking 2020–22 detail</summary>

- **2020-22 (sole engineer on the codebase):**
  - Symfony Console bulk-email campaign command with active-account rotation, per-account delays and PID-stamped logs.
  - DB-backed system settings page (global VAT rate, PDF font-size live preview) propagating to server code, JavaScript and PDFs.
  - Modular order and timed-invoice calculation (VAT and non-VAT customers, quantities, discounts, postage, editable or rounded totals), consistent across PHP, JavaScript and generated PDFs.
  - Customer-notes module (types, open/closed status, filters, pagination) and image upload with resize.
  - Bootstrap 4 to 5 migration with assets moved to a CDN to improve load times.
  - Invoice filename-uniqueness checks and safer folder creation.
  - Per-user invoice folders with admin options to copy, move or remove existing invoices; a sent-invoice browser with filters, preview and path copy.
  - Feature-branch workflow with semantic version tags (v0.8.7 to v1.0.1) and a manual regression checklist.

</details>

- Ran and maintained bulk email workflows that processed 500k+ transactional and marketing emails, including invoices and campaign communications.

**Stack:** PHP, Symfony, MySQL, REST APIs, PHPStan, Deptrac, Bootstrap, cPanel

### BYND Smart Home - frontend platform migration

- Rebuilt a smart-home and yacht control SPA in **Vue on Microsoft FAST** (previously Aurelia), writing about 97% of the code, began its Vue 3 migration and built real-time device interactions over MQTT and Socket.IO.
- Architected smart-home API infrastructure with **MQTT and FeathersJS**, reusable Vue components and modular Vuex state for two-way device control.
- Built browser lifecycle-aware connection management with recovery after connectivity loss, reconnecting when appropriate to avoid unnecessary network traffic and backend load.
- Contributed to a Storybook-led component system that reduced UI bugs by 40%, and developed a dynamic floor-plan editor.
- Presented the product at client events; the positive feedback supported further development funding.

<details>
<summary>BYND engineering detail</summary>

- **MQTT conventions:** QoS 1 with retained messages and persistent sessions for important topics, plus a last-will message to flag unexpected disconnects, with reconnect and offline handling.
- **Device abstraction:** shared base device and source classes (TV receiver, AV source); per-device Vuex modules (thermostat, audio, TV receiver, zone-to-area) with shared type constants for multiple devices.
- **Real-time controls:** debounced events and non-visual components so sliders publish updates without flooding the broker; solved two-way binding for FAST form-associated components.
- Migrated to FAST v2 (a breaking-change refactor) and kept it current.
- Reusable D-pad, num-pad, playback and preset controls, a central icon component, and Storybook stories with a shared FAST decorator.
- Earlier Aurelia admin app: refactored grids into a shared Slickgrid helper and built channel/package management with search, filters and duplication.

</details>

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
| **Backend**  | PHP 8, Laravel, Symfony, Yii2, Statamic, REST APIs, OpenAPI (Scramble), GraphQL, MySQL/MariaDB, SQL optimisation    |
| **Frontend** | JavaScript (TypeScript in personal projects), Vue 2/3, Nuxt, Tailwind CSS, Algolia, HTML/CSS, Storybook; Angular, Aurelia, jQuery (legacy) |
| **Platform** | Git, GitHub Actions, Docker, Linux, Nix, Apache, CI/CD, scheduled jobs and queues                                   |
| **Quality**  | PHPUnit, PHPStan, Deptrac, Vitest, Cypress, Selenium, Postman/Bruno, JMeter, SonarQube, integration and E2E testing                   |
| **Practices** | Agile (Scrum, Kanban), UML class and sequence diagrams, design patterns (MVC, Factory, Command, ActiveRecord, Iterator) |
| **Security** | OWASP, CSP, XSS/CSRF/SQL-injection mitigation, dependency vulnerability remediation                                 |

## Education and Certifications

- Master of Technology (M.Tech) in Software Engineering, with honours
- Bachelor's degree in Software Development and Testing, with honours
- BA in Philology (Germanic Languages and Literatures, Translation)
- QATestLab Certified Test Engineer
- British Council EnglishScore C1 (599, maximum score)
