# Pastry POS 🧁

A mobile point-of-sale app I'm building for pastry shops and small food businesses.

The goal is simple: make it easier to manage products, orders, and sales from one place, without turning everyday operations into extra work.

![React Native](https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?logo=expo)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

## Screenshots

| Dashboard | Orders | Inventory |
|:---:|:---:|:---:|
| Coming soon | Coming soon | Coming soon |

## Features built so far

- **Product catalog:** create, edit, and organize products and categories, with product images.
- **Point of sale:** build a cart, check out, and record sales.
- **Flexible payments:** accept partial payments and complete outstanding balances from sales history.
- **Sales history:** browse past sales and review transaction details.
- **Initial inventory:** register starting stock for products without requiring a production recipe, with optional expiration dates.
- **Multi-branch foundation:** organization and branch onboarding with role-aware access.
- **Authentication:** email/password, Google, and Apple sign-in flows.

The app is **still in development**. Features listed here are implemented in the private codebase, not a claim of a production launch.

## Under the hood

The app is built with **React Native, Expo, and TypeScript**, with **Supabase and PostgreSQL** on the backend.

The interface uses **HeroUI Native** and a Lavender theme. **TanStack Query** manages server-state fetching and cache invalidation. I'm using **Jest / React Native Testing Library** and **pgTAP** database tests to catch regressions, alongside Conventional Commits, CI, and Release Please to keep changes organized.

The private codebase also includes role-based access checks and database-level safeguards around inventory operations.

## Updates

Selected milestones from the private project's release history, summarized without exposing its source code or internal infrastructure.

<!-- RELEASES:START -->
- **v1.8.1 · Nov 7, 2026** — Tightened database permissions for initial stock registration.
- **v1.8.0 · Nov 7, 2026** — Added initial inventory tracking for products without production recipes.
- **v1.7.0 · Oct 30, 2026** — Added partial payments, sales history, and the ability to complete pending payments.
- **v1.6.0 · Oct 29, 2026** — Introduced the POS checkout flow and improved product editing.
- **v1.5.0 · Oct 29, 2026** — Added product images and catalog UI improvements.
- **v1.4.0 · Oct 20, 2026** — Added product catalog management.
- **v1.2.0 · Oct 19, 2026** — Added organization and branch onboarding.
- **v1.0.0 · Oct 17, 2026** — Initial authentication and theme foundation.
<!-- RELEASES:END -->

## About

I'm [Erick Beltran](https://github.com/edcastsh), a software engineer working on web and mobile products.

[Portfolio](https://edcastsh.vercel.app) · [LinkedIn](https://www.linkedin.com/in/erickedelbeltran)

The application code is kept in a private repository while the product is in development.
