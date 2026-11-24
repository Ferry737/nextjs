<div align="center">

# nextjs

**A Next.js sandbox pre-configured for AI-assisted development.**
App Router + TypeScript + Tailwind + ESLint out of the box, plus `AGENTS.md` and `CLAUDE.md` so coding agents know the house rules before they touch a file.

[![Next.js](https://img.shields.io/badge/Next.js-App%20Router-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](./package.json)
[![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](./tsconfig.json)
[![Tailwind](https://img.shields.io/badge/Tailwind-v4-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white)](./postcss.config.mjs)
[![Live](https://img.shields.io/badge/Live-Vercel-00d4aa?style=for-the-badge&logo=vercel&logoColor=white)](https://nextjs-adamu737.vercel.app)

[Live demo](https://nextjs-adamu737.vercel.app) · [Agent rules](./AGENTS.md) · [Claude rules](./CLAUDE.md)

</div>

---

## 🧰 What's in it

| | |
|---|---|
| ⚡ **Next.js App Router** | `app/page.tsx` as the entry; file-based routing, server components, `next/font` with Geist. |
| 🟦 **TypeScript strict** | `tsconfig.json` with strict mode on. |
| 🎨 **Tailwind CSS** | PostCSS + Tailwind configured, ready for design tokens. |
| 🤖 **Agent-ready** | `AGENTS.md` (tool-agnostic) and `CLAUDE.md` (Claude Code) describe conventions, so AI edits stay consistent. |
| 🧹 **ESLint** | `eslint.config.mjs` flat config. |

> This is a **starter / sandbox**, not a product. It exists to spin up a new Next.js idea in under a minute with the agent guard-rails already in place.

## 🚀 Run

```bash
npm install
npm run dev        # http://localhost:3000
```

```bash
npm run build      # production build
npm run start      # serve it
npm run lint       # ESLint
```

## 📁 Layout

```
nextjs/
├── app/page.tsx        ← start here
├── AGENTS.md           ← rules for any coding agent
├── CLAUDE.md           ← rules for Claude Code
├── next.config.ts · tsconfig.json · postcss.config.mjs · eslint.config.mjs
└── package.json
```

## ☁ Deploy

Push to `main`; Vercel builds it. Or:

```bash
npx vercel
```

---

<div align="center">
<sub>Built by <a href="https://github.com/Ferry737">Ferry</a> · the clean slate every other Next.js project here started from.</sub>
</div>
