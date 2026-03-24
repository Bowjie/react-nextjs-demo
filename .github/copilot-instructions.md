# Copilot Notes For This Project

This repository is a fresh install using:

- Next.js 16.2.1
- React 19.2.4
- React DOM 19.2.4
- TypeScript 5
- ESLint 9 + eslint-config-next 16.2.1
- Tailwind CSS 4

When generating or changing code, follow these project rules:

1. Use App Router conventions with the `app/` directory.
2. Prefer Server Components by default; add `"use client"` only when browser-only behavior is required.
3. Keep changes minimal and aligned with a fresh Next.js setup unless a feature request requires structure changes.
4. Use TypeScript-first patterns with explicit types where they improve clarity.
5. Preserve compatibility with React 19 and Next.js 16 APIs.
6. Avoid adding new dependencies unless clearly necessary.
7. Keep components accessible and responsive by default.
8. Keep styling consistent with existing project setup (global CSS and Tailwind v4 where appropriate).
9. Update `README.md` when adding non-trivial setup, scripts, or architecture changes.
10. Validate meaningful changes with `npm run lint` and `npm run build`.

Implementation preferences:

- Favor clear, small components over large monolithic files.
- Prefer simple data flow and predictable state management.
- Do not refactor unrelated areas while implementing a focused task.
