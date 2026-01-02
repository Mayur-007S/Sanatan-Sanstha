# 🤖 Agent & Developer Guidance

Welcome to the **Swabhav Dosh Sarni** project. This document provides essential context and rules for agents (AI) and developers working on this codebase.

## 1. Project Overview
This is a **client-side only** Progressive Web App (PWA) designed for spiritual self-improvement. It relies entirely on `index.html` (Vanilla JS + Tailwind via CDN) and `sw.js` (Service Worker) for offline capabilities.

**Key constraints:**
- **No Build Step:** The project uses Tailwind CSS via CDN script. Do not introduce npm build steps unless explicitly requested.
- **Local Storage:** All data is persisted in `localStorage`. **NEVER** clear or alter the schema of `ss_wrong_logs_v2` without a migration strategy, as this will delete user data.
- **Offline First:** Ensure new features work without internet (except translation/CDN loading initially).

## 2. Development Standards
- **Single File Components:** Most logic lives in `index.html`. Keep sections modularized with clear comments (e.g., `// --- Wrong Things Logic ---`).
- **Styling:**
  - Use **Tailwind utility classes** for standard styling.
  - Refer to `docs/style.md` for the official color palette and typography.
  - Avoid inline `style="..."` attributes; use `main.css` for complex overrides if necessary.
- **Accessibility:**
  - Maintain high contrast text (Slate-600+).
  - Ensure interactive elements are touch-friendly (mobile-first design).

## 3. Important Design Tokens
*Refer to [Brand Style Guide](docs/style.md) for full details.*

- **Primary Brand:** Orange-800 (Text), Orange-100 (Borders)
- **Secondary:** Blue-800 (Navigation)
- **Actions:** Emerald-600 (Save/Submit)

## 4. Critical Files
- `index.html`: The application core (HTML/JS/Tailwind).
- `manifest.json`: PWA configuration.
- `sw.js`: Service Worker for caching assets.
- `docs/style.md`: Design system source of truth.

## 5. Common Tasks
- **Updating Logic:** Search for the specific function (e.g., `renderWrong`) in `index.html` and modify carefully.
- **Adding Assets:** Update `sw.js` > `ASSETS` array to ensure new files are cached.
- **Debugging:** Use `console.log` during dev, but keep production code clean.

## 6. Tone & Voice
When adding text content:
- Use **polite, spiritual, and encouraging** language.
- Maintain bilingual support (Marathi/English) logic where possible.

---
*This file is for AI agents and developers to understand the project context quickly.*
