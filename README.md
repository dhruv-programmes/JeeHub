<div align="center">

# JeeHub

### Your only hub for PYQs.

**Practice smarter. Revise faster. Get exam-ready.**

A lightweight, browser-based PYQ and mock-test platform that brings previous-year examination papers together in one place — without sign-ups or distractions.

<br />

<a href="https://jeehub.vercel.app/home">
  <img src="https://img.shields.io/badge/Live_Demo-Open_JeeHub-2563EB?style=for-the-badge" alt="Live Demo" />
</a>
<a href="https://github.com/dhruv-programmes/JeeHub">
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" alt="GitHub Repository" />
</a>
<a href="https://github.com/dhruv-programmes/JeeHub/blob/main/LICENSE">
  <img src="https://img.shields.io/badge/License-MIT-2EA44F?style=for-the-badge" alt="MIT License" />
</a>

<br /><br />

![GitHub Stars](https://img.shields.io/github/stars/dhruv-programmes/JeeHub?style=social)
![GitHub Forks](https://img.shields.io/github/forks/dhruv-programmes/JeeHub?style=social)
![GitHub Issues](https://img.shields.io/github/issues/dhruv-programmes/JeeHub)
![Last Commit](https://img.shields.io/github/last-commit/dhruv-programmes/JeeHub)

<br />

**Built with**

[![Next.js](https://img.shields.io/badge/Next.js-14.1-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Radix UI](https://img.shields.io/badge/Radix_UI-Primitives-161618?style=for-the-badge)](https://www.radix-ui.com/)
[![Lucide](https://img.shields.io/badge/Lucide-Icons-F67373?style=for-the-badge)](https://lucide.dev/)
[![KaTeX](https://img.shields.io/badge/KaTeX-Math_Rendering-1A1A1A?style=for-the-badge)](https://katex.org/)
[![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

<br /><br />

**1,000+ PYQs · 200+ Mock Tests · Multiple Exam Categories**

</div>

---

## Table of Contents

- [Overview](#overview)
- [Why JeeHub?](#why-jeehub)
- [Features](#features)
- [Examination Library](#examination-library)
- [Application Routes](#application-routes)
- [Technology Stack](#technology-stack)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Maintainer](#maintainer)

---

## Overview

**JeeHub** is an exam-practice platform built to make previous-year questions and full examination papers easier to find and attempt.

Preparation resources are often scattered across different websites, PDFs and folders. JeeHub brings a growing collection of past examination papers into a single, accessible interface so students can spend less time searching for material and more time practising.

The platform is designed around a simple idea: open the site, find an examination paper, and start solving.

<div align="center">

| **1,000+** | **206** | **No account** |
|:---:|:---:|:---:|
| PYQs advertised on the landing page | Tests listed in the inspected catalogue | Required to browse the public catalogue |

<sub>Catalogue count reflects the live site at the time this README was prepared and may change as papers are added.</sub>

</div>

## Why JeeHub?

- **Practice without friction:** Browse the available papers without creating an account.
- **Less clutter:** An ad-free experience focused on the study material.
- **A focused interface:** Find an exam paper and open it as a mock test.
- **Comfortable viewing:** Dark-mode support for extended study sessions.
- **A growing library:** Access papers from multiple examination years and categories.

> **The goal:** Make previous-year paper practice as straightforward as opening a website and getting started.

## Features

### Centralized PYQ Library

- A single catalogue for previous-year examination papers.
- Papers organized by examination, year, date and shift wherever the information is available.
- Historic paper collections spanning multiple years.
- A catalogue that can grow as additional papers are added.

### Mock-Test Access

- Open a listed paper through its **Solve** action.
- Attempt papers in a mock-test-oriented experience.
- Test entries expose details such as examination name, date, shift, duration and question count when available.

### Student-Focused Experience

- No account required to browse the public catalogue.
- Ad-free experience, as described on the landing page.
- Dark-mode support.
- Responsive web interface.
- Math-rendering support through KaTeX dependencies in the project.

## Examination Library

The live catalogue includes papers from several competitive examinations and their historical formats.

| Examination | Available material |
|:---|:---|
| **JEE Main** | Previous-year papers, sessions and shifts |
| **JEE Advanced** | Paper 1 and Paper 2 collections |
| **NEET** | Previous-year medical entrance papers |
| **BITSAT** | Previous-year examination paper collection |
| **Historical examinations** | Legacy collections such as IIT-JEE, AIEEE and AIPMT where listed |

The catalogue displayed **206 tests** during the latest inspection. Availability and count can change as the library is updated.

## Application Routes

The following route map describes the public-facing experience and the mock-test route pattern used by the application.

| Route | Page | Purpose |
|:---|:---|:---|
| `/` | Landing page | Introduces JeeHub, its study-focused approach and the entry point to the application. |
| `/home` | PYQ catalogue | Displays the available mock tests and their examination details. |
| `/mock-test/[paper]` | Mock-test page | Opens a selected paper using its catalogue identifier. |

`[paper]` is a dynamic paper identifier supplied by the catalogue. Individual identifiers depend on the papers available in the deployed catalogue.

## Technology Stack

JeeHub is built with the Next.js App Router and a component-based React interface.

### Core

<p>
  <a href="https://nextjs.org/"><img src="https://img.shields.io/badge/Next.js-14.1-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" /></a>
  <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" /></a>
  <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /></a>
</p>

### Styling & Components

<p>
  <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Tailwind_CSS-3-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" /></a>
  <a href="https://www.radix-ui.com/"><img src="https://img.shields.io/badge/Radix_UI-Component_Primitives-161618?style=for-the-badge" alt="Radix UI" /></a>
  <a href="https://lucide.dev/"><img src="https://img.shields.io/badge/Lucide-Icons-F67373?style=for-the-badge" alt="Lucide" /></a>
  <a href="https://katex.org/"><img src="https://img.shields.io/badge/KaTeX-Math_Rendering-1A1A1A?style=for-the-badge" alt="KaTeX" /></a>
</p>

### Deployment & Monitoring

<p>
  <a href="https://vercel.com/"><img src="https://img.shields.io/badge/Vercel-Deployment-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" /></a>
  <a href="https://vercel.com/analytics"><img src="https://img.shields.io/badge/Vercel-Analytics-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel Analytics" /></a>
</p>

### Stack Breakdown

| Layer | Technology | Usage |
|:---|:---|:---|
| Framework | Next.js 14 | App Router and application rendering |
| UI | React 18 | Component-based user interface |
| Language | TypeScript 5 | Typed application code |
| Styling | Tailwind CSS 3 | Utility-first styling |
| UI primitives | Radix UI | Accessible interface primitives |
| Icons | Lucide React | Interface icons |
| Mathematics | KaTeX / react-latex-next | Mathematical notation rendering |
| Theme | next-themes | Theme handling |
| Analytics | Vercel Analytics | Deployment analytics integration |
| Hosting | Vercel | Application deployment |

> The version badges above reflect the dependencies in the publicly visible repository manifest. Update them when the dependency versions in your target branch change.

## Architecture

JeeHub uses a Next.js application structure with page routes, reusable React components and shared library data.

```text
                   ┌──────────────────────────────┐
                   │          STUDENT             │
                   │       Browser Client         │
                   └──────────────┬───────────────┘
                                  │
                                  ▼
                   ┌──────────────────────────────┐
                   │        NEXT.JS APP           │
                   │          app/                │
                   └──────────────┬───────────────┘
                                  │
                 ┌────────────────┴────────────────┐
                 │                                 │
                 ▼                                 ▼
      ┌──────────────────────┐        ┌────────────────────────┐
      │ Reusable Components  │        │ Shared Library Data   │
      │     components/      │        │        lib/            │
      └──────────┬───────────┘        └────────────┬───────────┘
                 │                                 │
                 └────────────────┬────────────────┘
                                  │
                                  ▼
                   ┌──────────────────────────────┐
                   │      PYQ / MOCK-TEST UI      │
                   │  Browse → Select → Attempt  │
                   └──────────────────────────────┘
```

### Main Application Areas

- **`app/`** — Next.js routes, layouts and global styles.
- **`components/`** — Reusable interface elements, including the exam catalogue and paper cards.
- **`lib/`** — Shared utilities and examination catalogue data.
- **`public/`** — Static assets served by the application.

## Getting Started

Run JeeHub locally to explore the codebase or contribute improvements.

### Prerequisites

- [Node.js](https://nodejs.org/) 20 or later recommended.
- npm (the repository includes an npm lockfile).
- Git.

### 1. Clone the repository

```bash
git clone https://github.com/dhruv-programmes/JeeHub.git
cd JeeHub
```

### 2. Install dependencies

```bash
npm install
```

For a clean install using the committed npm lockfile:

```bash
npm ci
```

### 3. Start the development server

```bash
npm run dev
```

Open **http://localhost:3000** in your browser.

### 4. Create a production build

```bash
npm run build
```

## Available Scripts

| Command | Description |
|:---|:---|
| `npm run dev` | Starts the Next.js development server. |
| `npm run build` | Creates an optimized production build. |
| `npm run lint` | Runs the configured lint command. |

> Check the scripts in `package.json` before using a production-start command. The publicly visible manifest currently maps `start` to `next dev`; for a conventional local production preview, the script should be `next start` after building.

## Project Structure

```text
JeeHub/
│
├── app/                      # Next.js App Router pages and layouts
│   ├── layout.tsx            # Root layout, theme provider and analytics
│   ├── page.tsx              # Main application page
│   └── globals.css           # Global styles
│
├── components/               # Reusable React components
│   ├── ExamList.tsx          # Examination catalogue sections
│   ├── ExamCard.tsx          # Individual paper card and Solve action
│   ├── Header.tsx            # Application heading
│   └── ui/                   # Shared UI primitives
│
├── lib/                      # Shared utilities and catalogue data
│   └── examInfo.ts           # Examination metadata and paper identifiers
│
├── public/                   # Static files and public assets
│
├── components.json           # UI component configuration
├── next.config.mjs           # Next.js configuration
├── package.json              # Dependencies and scripts
├── package-lock.json         # npm dependency lockfile
├── tailwind.config.ts        # Tailwind CSS configuration
├── tsconfig.json             # TypeScript configuration
└── README.md                 # Project documentation
```

*The tree highlights the principal directories and files; additional route and component files may exist in the repository.*

## Deployment

JeeHub is hosted on Vercel.

**Live application:** https://jeehub.vercel.app/home

To deploy your own copy:

1. Fork the repository.
2. Import the fork into [Vercel](https://vercel.com/).
3. Select the Next.js framework preset.
4. Keep the build command aligned with the repository's `package.json`.
5. Deploy the project.

For subsequent updates, push commits to the connected Git branch and Vercel can build and deploy the new version.

## Contributing

Contributions are welcome. You can help improve JeeHub by fixing bugs, improving the interface, refining the paper catalogue, enhancing accessibility or improving documentation.

### Contribution workflow

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feat/your-feature
   ```

3. Make your changes and test them locally.
4. Commit your work:

   ```bash
   git add .
   git commit -m "feat: describe your changes"
   ```

5. Push your branch:

   ```bash
   git push origin feat/your-feature
   ```

6. Open a Pull Request with a clear description of the changes.

For bugs or feature requests, use the [GitHub Issues](https://github.com/dhruv-programmes/JeeHub/issues) page.

## License

JeeHub is distributed under the **MIT License**. See the [LICENSE](LICENSE) file for the complete license text.

## Maintainer

**Dhruv Padhiyar** — Creator and maintainer of JeeHub.

- GitHub: [@dhruv-programmes](https://github.com/dhruv-programmes)
- Repository: [dhruv-programmes/JeeHub](https://github.com/dhruv-programmes/JeeHub)

---

<div align="center">

### Built for focused practice. Made for every PYQ solver.

**JeeHub — Your only hub for PYQs.**

[Open JeeHub](https://jeehub.vercel.app/home) · [⭐ Star the repository](https://github.com/dhruv-programmes/JeeHub) · [Contribute](https://github.com/dhruv-programmes/JeeHub/pulls)

</div>
