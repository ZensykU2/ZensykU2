<h1 align="center">Cristian Torre</h1>

<p align="center">
  Software development apprentice from Switzerland.<br>
  I build desktop applications, systems tools, and full-stack web platforms.
</p>

<p align="center">
  <a href="mailto:crto.CT@gmail.com"><img src="https://img.shields.io/badge/Email-crto.CT%40gmail.com-0f172a?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/ZensykU2?tab=repositories"><img src="https://img.shields.io/badge/Repositories-15-0f172a?style=flat-square&logo=github&logoColor=white" alt="Repositories"></a>
  <img src="https://img.shields.io/badge/Location-Switzerland-0f172a?style=flat-square" alt="Switzerland">
</p>

---

## About

I am training as a software developer and spend most of my free time building things that
actually ship: a native Windows debugger written against the Win32 API, a Tauri and Rust
file launcher backed by SQLite full-text search, an Electron application doing real
bookkeeping for a Swiss alpine cabin, and a type-safe Next.js publishing platform. Desktop
is where I am most at home — I have shipped production apps on both Electron and Tauri and
can argue the trade-off from experience rather than from blog posts.

My focus is on writing code that other people can read, clear architecture, documented
edge cases, and projects that are finished rather than abandoned. I am strongest in
**C#**, **TypeScript**, **Go**, and increasingly **Rust** and **C++**.

**Currently:** finishing my apprenticeship, deepening my systems programming skills, and
aiming to study Game Development & Design at HSLU.

---

## Tech Stack

| Area | Technologies |
|:--|:--|
| **Languages** | C++20, C#, TypeScript, Rust, Go, Python, PowerShell, SQL |
| **Frontend** | React, Next.js, Vite, Tailwind CSS, Zustand, TanStack Query |
| **Backend** | .NET 8, tRPC, FastAPI, Drizzle ORM, Auth.js, Node.js |
| **Desktop** | Electron, Tauri, WinForms / WPF, Win32 & DbgHelp APIs |
| **Data** | PostgreSQL, SQLite, SQLite FTS5 |
| **Tooling** | Docker, CMake, Git, Vitest, Inno Setup, NSIS |

---

## Selected Projects

### Featured

**[WinDebug](https://github.com/ZensykU2/WinDebug)** — `C++20` `Win32` `CMake`

A mini 64-bit Windows debugger written directly against the Win32 Debugging API. Launches
or attaches to processes, plants `INT3` and hardware breakpoints with correct RIP rewind
and re-arming, reads and writes remote memory and registers, walks call stacks through
DbgHelp, and parses PE files from disk or a live image. Built to be read: every non-obvious
interaction with the Windows debugging model is documented where it happens.

**[Trace](https://github.com/ZensykU2/trace)** — `Rust` `Tauri` `React` `SQLite`

A local-first file launcher. A Rust indexer feeds a SQLite FTS index for instant search
across configured roots, with live file watching, watcher-overflow fallback, bounded
diagnostics, and a full local-data reset path. Nothing about the user's filesystem leaves
the device — the privacy model is specified table by table in the README.

**[Wädi Alphütte — Finance & Budget Manager](https://github.com/ZensykU2/WaediAlphuette)** — `Electron` `React` `TypeScript` `SQLite`

A bookkeeping application built for a real Swiss alpine cabin. Its core is a beverage
settlement system that tracks three distinct consumption streams — guest sales at retail
price, self-consumption at cost price, and helper consumption at zero revenue — with
automatic weekly snapshots, ledger integration, budget monitoring, Recharts reporting, and
Excel export. Fully localized in German, tested with Vitest, and documented for both end
users and developers.

### Desktop & Tooling

**[WeeklyScheduleCreator](https://github.com/ZensykU2/WeeklyscheduleCreator)** — `Electron` `React` `TypeScript`

A weekly planner focused on interface fluidity: hardware-accelerated transitions, a full
undo/redo history stack, persistent versus one-time entries, custom day and task presets,
and reactive German/English switching. Distributed as a packaged desktop release.

**[GardenDocGen](https://github.com/ZensykU2/GardenDocGen)** — `C#` `.NET 8` `Inno Setup`

A document automation tool that turns garden plot inspection data into finished Word
protocols, with YAML-driven article management, editable templates, and automatic date and
deadline formatting. Shipped as a signed Windows installer with bilingual documentation.

### Systems & Networking

**[Go Reverse Proxy](https://github.com/ZensykU2/Go-reverse-proxy)** — `Go` `React` `Docker`

A reverse proxy written from scratch in Go with round-robin load balancing, three-second
backend health checks, and process supervision of its own backends. Ships with a React
dashboard for start/stop/pause control, live status indicators, and a built-in request
tester.

**[HTTP Server in Go](https://github.com/ZensykU2/HTTP-Server-GO)** — `Go`

An HTTP server built on raw TCP with no external dependencies, written to understand the
protocol rather than to consume a framework.

### Web & Services

**[Blog Platform](https://github.com/ZensykU2/blog-app)** — `Next.js 16` `tRPC` `Drizzle` `PostgreSQL`

A full-stack publishing platform on the T3 stack: end-to-end type safety from database to
client, OAuth and credential authentication via Auth.js, a custom Markdown editor with live
preview, image cropping for avatars and banners, and social features including follows,
likes, bookmarks, and notifications.

**[SSL/TLS Checker](https://github.com/ZensykU2/SSL-Checker)** — `Python` `FastAPI` `PostgreSQL` `Docker`

A certificate monitoring service that tracks expiry dates across registered domains and
sends email alerts before they lapse. Fully containerized with Docker Compose alongside
PostgreSQL and pgAdmin.

**[Habitica ↔ Google Tasks Sync](https://github.com/ZensykU2/Habitica-GoogleTask-Sync)** — `TypeScript` `Vite` `Chrome Extension`

A browser extension performing two-way synchronization between Habitica and Google Tasks,
including completion and deletion propagation and difficulty mapping between the two task
models.

### Automation & Scripting

**[WinSecureCheck](https://github.com/ZensykU2/ProjektM431_M122)** — `PowerShell 7`

An automated Windows security audit that runs a suite of modular checks and produces a
scored report from 0 to 100, with optional network reachability tests. Structured as an
orchestrator over independent check modules, with its own test suite.

---

## GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ZensykU2&show_icons=true&theme=transparent&hide_border=true&hide_title=true" alt="GitHub statistics" height="150">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ZensykU2&layout=compact&theme=transparent&hide_border=true&hide_title=true" alt="Top languages" height="150">
</p>

---

## Contact

I am open to apprenticeship-adjacent work, internships, and collaboration on open-source
tooling.

- Email — [crto.CT@gmail.com](mailto:crto.CT@gmail.com)
- GitHub — [@ZensykU2](https://github.com/ZensykU2)
