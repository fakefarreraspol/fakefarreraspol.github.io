# Agent Guidance

## Commands
- `bun install` - Install dependencies
- `bun dev` - Start dev server at `localhost:4321`
- `bun build` - Build for production
- `bun preview` - Preview production build locally
- `bun astro check` - Run Astro type checking

## Tech Stack
- **Astro v6** with Tailwind CSS v4
- **Bun** as package manager (not npm/yarn/pnpm)
- **Node.js >= 22.12.0** required

## Tailwind v4 Setup
Uses the new v4 syntax in `src/styles/global.css`:
```css
@import "tailwindcss";
```
Do NOT use v3 syntax (`@tailwind base/components/utilities`).

## Available Skills
Skills in `.agents/skills/` provide specialized guidance for:
- Astro framework
- Tailwind CSS v4
- Accessibility (WCAG)
- Frontend design
- TypeScript advanced types
- Bun tooling