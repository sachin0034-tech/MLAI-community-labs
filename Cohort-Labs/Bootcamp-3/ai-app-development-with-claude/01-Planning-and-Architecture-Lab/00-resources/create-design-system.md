# How to Create Your Own Design System

## Steps

1. Open the Claude Code apps

![image](./design/1.png)

2. Click on the design system file

![image](./design/3.png)

3. Express your ideas to Claude — describe what you want your app to look like. See the example prompt below:

![image](./design/4.png)

```
Create a complete design system inspired by the visual quality, aesthetics, and user experience of Anthropic's website.

Reference website:
https://www.anthropic.com

Requirements:

* Analyze the overall design language, typography, color palette, spacing, layouts, and component patterns.
* Capture the premium, minimal, and AI-first aesthetic while creating an original design system.
* Document the entire system in a `design.md` file.
* Include design tokens, Tailwind CSS mappings, reusable components, responsive layouts, accessibility guidelines, animation principles, and UI patterns.
* The `design.md` file should serve as the single source of truth for the application's design and frontend development.

```

**Or instead of describing in words, you can:**

- **Attach a screenshot** — take a screenshot of any design you like and drop it into Claude with the prompt: `"Create a design system based on this screenshot and save it to @.claude/knowledge/design-system.md"`
- **Add a Figma link** — paste your Figma file URL and ask Claude to extract the design system from it
- **Add a website link** — paste any website URL and ask Claude to create a design system that matches its style
