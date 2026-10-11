# Test Project

This is a **Node.js** project written in **TypeScript**.

## Stack

- Runtime: Node.js
- Language: TypeScript (`.ts`)
- Package manager: npm
- Module system: ES modules (`"type": "module"`)

## Rules for the agent

- Use Node.js APIs and npm packages. Do not introduce other runtimes (Python, Deno, Bun) unless asked.
- Write all application code in TypeScript. Avoid plain JavaScript (`.js`) source files.
- Keep types explicit. Prefer interfaces/types over `any`.
- Use `strict` TypeScript settings.
- Put source files in `src/`.
- Put compiled output in `dist/`.
- Use `tsx` or `ts-node` for local runs; use `tsc` for production builds.
- Prefer native Node.js modules (`node:fs`, `node:path`, `node:http`) when they are enough.
- Follow Node.js + TypeScript conventions for scripts, errors, and async code (`async`/`await`).

## Scripts

- `npm run dev` — run with tsx (watch)
- `npm run build` — compile TypeScript to `dist/`
- `npm start` — run compiled output
- `npm run typecheck` — type-check without emitting files

## Layout

```
test project/
  src/
    index.ts
  package.json
  tsconfig.json
  cursor.md
```
