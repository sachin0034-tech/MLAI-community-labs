# Lab 1 — Planning & Architecture

**Part 1 of 3** in the ContractIQ build path: [Lab 1: Planning](./readme.md) → [Lab 2: Building the Application](../02-Building-the-Application-Lab/readme.md) → [Lab 3: Security & Deployment](../03-Security-and-Deployment-Lab/readme.md)

> **New here?** Make sure you've finished **[Getting Started](../00-Getting-Started/readme.md)** first — it gets your tools installed and explains every term used below. Any word that confuses you in this lab is probably in that page's glossary.

---

## What This Lab Is, In Plain Words

This is the **"think before you build"** lab. You will not write or generate any application code here. Instead you'll:

- Understand the actual problem you're solving and who it's for
- Get your own copy of a ready-made starter project
- Learn how Claude Code's reusable instructions ("skills") work
- Look at the colors/fonts/spacing rules ("design system") the app will follow
- Turn the product idea into a written, step-by-step build plan

Think of this lab as drawing the blueprint before anyone picks up a hammer. Skipping it doesn't save time — it just moves the confusion to later, when it's more expensive to fix (e.g. realizing halfway through building a screen that the database is missing a piece of information it needed all along).

No prior coding or AI experience is required. Every step assumes this is the first time you've done it.

---

## Lessons in This Lab

| # | Lesson | What You Do |
|---|---|---|
| 1 | [Project Foundation](./01-project-foundation/readme.md) | Understand the problem you're solving, fork the starter repo, clone it, and open it in VS Code |
| 2 | [Skills and the Design System](./02-skills-and-design-system/readme.md) | Learn how Claude Code skills work and review the design system that will govern the app's UI |
| 3 | [Engineering Planning](./03-engineering-planning/readme.md) | Use Plan Mode to turn the product requirements into an architecture document and file-by-file implementation specs |

---

## What You Will Build Toward

Across this lab you will plan **ContractIQ** — a web app where a user uploads a contract PDF and gets back a structured, page-cited breakdown of every clause that matters, plus a chat interface to ask follow-up questions about the document.

You won't write a line of frontend or backend code in this lab. What you *will* produce by the end:

- A local clone of the starter repository, open and ready in VS Code
- A clear mental model of the product, its users, and what "done" looks like
- An understanding of the five Claude Code skills that drive the rest of the build
- The design system (`docs/design.md`) that every screen will follow
- `docs/engineering/engineering-doc.md` — the architecture plan
- `docs/engineering/implementation-specs.md` — the file-by-file build blueprint

These last two documents are what Lab 2 is built from. Nothing in Lab 2 makes sense without them.

---

## Tech Stack Decided in This Lab

| Layer | Technology | Why |
|---|---|---|
| Frontend | Next.js 14, TypeScript, Tailwind CSS | Full-stack React framework, type safety, utility-first styling that maps cleanly to a design system |
| Database & Auth | Supabase (PostgreSQL + Auth) | Hosted Postgres with built-in auth and Row Level Security, generous free tier |
| AI | Claude API (Anthropic) / OpenAI | Powers the contract analysis and chat features |
| Planning & Build Tool | Claude Code | Plans, writes, secures, and helps ship the application |

This stack is fixed in the starter repo you fork in Lesson 1 — you are not choosing it from scratch, but you should understand *why* each piece is there before you build on top of it.

---

## Where to Drop Screenshots

Every lesson folder in this lab has its own `images/` subfolder, and the existing screenshots from the original walkthrough have already been copied in and are wired up — you don't need to add anything to follow along. If you want to **recapture your own screenshots** (recommended if any tool's UI has changed since this was written), drop the new image into the matching lesson's `images/` folder using the **same filename** that's already there (e.g. replace `01-project-foundation/images/3.png` with your own screenshot of the same step) — the lesson's `readme.md` already points at that filename, so nothing else needs to change.

---

## Up Next

Start with [Lesson 1 — Project Foundation](./01-project-foundation/readme.md).

When all three lessons are complete, continue to **[Lab 2 — Building the Application](../02-Building-the-Application-Lab/readme.md)**.
