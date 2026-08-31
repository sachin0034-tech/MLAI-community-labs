# AI App Development with Claude Code

**You don't need any coding experience to do this course.** You're going to build a real, working AI web app — with an AI assistant called Claude Code doing the actual typing, while you make the decisions and check the work.

By the end, you'll have built and published **ContractIQ**: a website where someone uploads a contract PDF and instantly gets a plain-English breakdown of what's in it, plus a chat box to ask follow-up questions about the document.

**New to all of this?** Start with **[Getting Started](./00-Getting-Started/readme.md)** — it walks you through installing the few free tools you need and explains every piece of jargon used anywhere in this course.

---

## The Three Labs

The course is split into three labs. Do them **in order** — each one needs files produced by the one before it.

| Lab | In Plain Words | Lessons |
|---|---|---|
| **[Lab 1 — Planning & Architecture](./01-Planning-and-Architecture-Lab/readme.md)** | Figure out *what* you're building and *how it should be put together* — before touching any code | 3 |
| **[Lab 2 — Building the Application](./02-Building-the-Application-Lab/readme.md)** | Actually build it — the screens, the database, the AI features — and run it on your own computer | 2 |
| **[Lab 3 — Security & Deployment](./03-Security-and-Deployment-Lab/readme.md)** | Lock the doors (fix security mistakes), then publish it to the internet so anyone can use it | 2 |

```
Getting Started   →   Lab 1: Plan it   →   Lab 2: Build it   →   Lab 3: Secure & ship it
(install tools)        (no code yet)        (runs on your        (live on the internet)
                                              computer only)
```

---

## What You Will End Up With

- A real web app, ContractIQ, that you built and can show people
- PDF upload with AI-powered contract analysis
- A chat box that remembers what you talked about earlier
- A real database (Supabase) with proper access control
- Login/signup that actually works
- A codebase with the common security mistakes already fixed
- A live web address anyone can visit — and that updates itself every time you make a change

---

## The Tools Behind It (You Don't Need to Know These Yet)

| Layer | Tool | In Plain Words |
|---|---|---|
| What the user sees | Next.js, TypeScript, Tailwind CSS | The website itself — pages, buttons, colors |
| Where data is stored | Supabase | A free, hosted database with built-in logins |
| The "brains" | Claude API / OpenAI | The AI that reads contracts and answers questions |
| Going live | Netlify | A free service that puts your app on the internet |
| Doing the building | Claude Code | The AI assistant you direct throughout this course |

You'll meet each of these one at a time, exactly when you need them — you never need to research any of this in advance.

---

## How Every Lesson Is Organized

So you always know what to expect:

- **What You Need Before Starting** — a quick checklist
- **Step-by-step instructions** — including the exact text to paste into Claude Code, word for word
- **Screenshots** — in that lesson's own `images/` folder, shown inline so you can compare what you see to what you should see
- **What You Have Built / What You Learned** — a plain-language recap at the end
- **If Something Breaks** — copy-paste prompts for the most common problems, where relevant

---

## Screenshots — Where to Put Them

Every lesson folder has its own `images/` subfolder right next to its `readme.md`, and the screenshots are already in place — you don't need to add anything to get started.

If a website's design changes after this course was written and a screenshot no longer matches what you see: take your own screenshot and save it **over the existing file, using the exact same filename** (e.g. `02-Building-the-Application-Lab/01-building-the-application/images/6.png`). Because the lesson text points at that filename — not its contents — nothing else needs to change.

Two spots don't have a screenshot yet, and the lesson text says exactly what to capture if you want to add one:
- `03-Security-and-Deployment-Lab/01-security-foundation/`
- `03-Security-and-Deployment-Lab/02-deployment/` (one missing image near the end)

---

## Start Here

1. **[Getting Started](./00-Getting-Started/readme.md)** — install your tools, learn the words
2. **[Lab 1 — Planning & Architecture](./01-Planning-and-Architecture-Lab/readme.md)** — begin the course
