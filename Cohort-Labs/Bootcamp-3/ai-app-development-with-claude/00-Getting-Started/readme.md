# Getting Started — Read This First

**You don't need to know how to code to finish this course.** You do need a few free tools installed on your computer and a handful of words explained before the lessons make sense. This page does both. Read it once, before Lab 1.

If a word ever confuses you later in any lesson, come back to the **Glossary** section below — every term used anywhere in this course is explained here in plain English.

---

## What You're Actually Going to Do

Across three labs, you're going to build a real web app called **ContractIQ** — something you could show a friend and they could actually use in their browser. You won't write the app's code yourself, line by line. Instead, you'll talk to an AI assistant called **Claude Code**, describe what you want, review what it builds, and approve or correct it. Your job is to **direct**, not to type every line of code.

That's it. That's the whole course. Now let's get your computer ready.

---

## Tools You Need to Install

Install these once, in this order. Each one is free.

| # | Tool | What It's For | Where to Get It |
|---|---|---|---|
| 1 | **A GitHub account** | Stores your project online and tracks your changes | [github.com/signup](https://github.com/signup) — just an email and password |
| 2 | **Git** | The program that actually does the saving/tracking GitHub displays | [git-scm.com/downloads](https://git-scm.com/downloads) — download and click through the installer with default options |
| 3 | **VS Code** | The program you'll write and view files in | [code.visualstudio.com](https://code.visualstudio.com/) — download and install like any other app |
| 4 | **Node.js** | Lets your computer run the JavaScript-based app you're building | [nodejs.org](https://nodejs.org/) — download the **LTS** version, click through the installer |
| 5 | **Claude Code** | The AI assistant that does the actual building, inside your terminal | Follow the install instructions at [claude.com/claude-code](https://claude.com/claude-code) — it needs Node.js (step 4) installed first |

> **How do I know it worked?** After installing Git and Node.js, open a terminal (see below if you don't know what that is) and type `git --version` then `node --version`. If each prints a version number instead of an error, you're set.

You do **not** need to sign up for Supabase, OpenAI, or Netlify yet — those come later in the course, exactly when you need them, with step-by-step instructions in the lesson that introduces them.

---

## Opening a Terminal Inside VS Code

You'll do this constantly throughout the course, so let's do it once together now.

1. Open VS Code.
2. Open the folder you're working in: **File → Open Folder**.
3. Open the terminal panel: click **Terminal** in the top menu, then **New Terminal** (or press `` Ctrl+` `` — the backtick key, usually top-left of your keyboard under Esc).
4. A panel appears at the bottom of the screen with a blinking cursor. This is the terminal. You type commands here and press **Enter** to run them.

Every lesson in this course will tell you exactly what to type into this terminal. You never need to guess.

---

## Glossary — Every Term Used in This Course

Read this once now, skim it, then come back any time a word trips you up.

| Term | Plain-English Meaning |
|---|---|
| **Terminal** (a.k.a. command line) | A way to control your computer by typing text commands instead of clicking icons. Faster once you're used to it, and it's how you talk to Claude Code. |
| **Repository** (a.k.a. "repo") | A project folder that Git is tracking the history of — every change ever made to it is saved, so you can always undo a mistake. |
| **Fork** | Making your own personal copy of someone else's repository on GitHub, under your own account, so you can change it freely without affecting the original. |
| **Clone** | Downloading a copy of a GitHub repository from the internet onto your own computer, so you can open and edit the files locally. |
| **Commit** | Saving a snapshot of your current changes, with a short message describing what you changed. Like hitting "Save" but with a note attached. |
| **Push** | Uploading your committed changes from your computer back up to GitHub, so they're backed up online and visible to others. |
| **IDE** (Integrated Development Environment) | A text editor built for writing code — VS Code is the one this course uses. It's like Microsoft Word, but for code. |
| **Frontend** | The part of an app you actually see and click on in your browser — buttons, pages, forms, colors. |
| **Backend** | The part of an app running on a server, out of sight, that handles logic, talks to the database, and calls the AI. |
| **Database** | A structured place to permanently store information — user accounts, uploaded contracts, chat messages. This course uses **Supabase** as the database. |
| **API** (Application Programming Interface) | A defined way for two pieces of software to talk to each other — for example, your app sending a question to Claude's API and getting an answer back. |
| **API key** | A secret password-like string that proves to a service (like OpenAI or Supabase) that your app is allowed to use it. Anyone with your key can rack up charges on your account — never share it or post it publicly. |
| **Environment variable** | A setting (often a secret key) stored outside your actual code, in a file called `.env.local`, so secrets don't end up visible in your source code. |
| **npm** (Node Package Manager) | A tool that downloads and installs the pre-built code "ingredients" (called packages) your app depends on, so you don't have to write everything from scratch. |
| **`npm run dev`** | The command that starts your app running on your own computer so you can view it in a browser, for testing before it's public. |
| **localhost / `localhost:3000`** | A web address that only works on your own computer — it means "this computer," not the public internet. This is where you test your app before it's live. |
| **Deploy** | Publishing your app to a public server so anyone on the internet can visit it at a real web address, not just `localhost`. |
| **Skill** (in Claude Code) | A saved, reusable set of instructions you trigger with a slash command like `/engineering-planner`. Covered in detail in Lab 1, Lesson 2. |
| **Plan Mode** | A mode in Claude Code where the AI thinks and proposes a plan but does not change any files until you approve it. Covered in Lab 1, Lesson 3. |
| **SQL** | The language used to create and query database tables. You won't write SQL by hand in this course — Claude generates it for you. |
| **Row Level Security (RLS)** | A database rule that ensures each user can only see their own data, even though everyone's data lives in the same table. |

---

## A Quick Cost-Saving Tip

AI models cost money to run, and some are more powerful (and more expensive/rate-limited) than others. Unless a lesson specifically tells you to use a particular model:

- Inside the Claude Code terminal, you can check or switch your active model with the `/model` command. If you're working through a lesson and hit a usage limit, switching to a smaller model (like a Haiku-class model) is usually enough to keep going.
- Inside the app itself, the lessons already tell Claude to use `gpt-4o-mini` for OpenAI calls — this is a smaller, cheaper model that's plenty capable for this course and won't burn through your API credits.

If you ever see a "rate limit" or "quota exceeded" error, this is almost always the fix.

---

## You're Ready

You now have:
- The five tools installed
- A terminal you know how to open inside VS Code
- A glossary to come back to whenever a word doesn't make sense

Head to **[Lab 1 — Planning & Architecture](../01-Planning-and-Architecture-Lab/readme.md)** to begin.
