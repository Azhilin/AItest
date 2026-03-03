# Copilot instructions for this repository

## Project context
- Stack: Vite + React + TypeScript.
- Entry points: `src/main.tsx` and `src/App.tsx`.
- Linting: ESLint flat config in `eslint.config.js`.
- Build: `npm run build` (`tsc -b && vite build`).

## Coding rules
- Keep changes minimal and scoped to the requested task.
- Preserve existing project structure and naming conventions.
- Prefer functional React components and TypeScript-first code.
- Avoid `any`; use explicit types or inference when clear.
- Do not add dependencies unless required for the task.
- Do not introduce unrelated refactors.

## React + TypeScript guidelines
- Use hooks and keep component logic simple.
- Keep components small and readable.
- Co-locate simple helpers near usage; move reusable logic to a utility only when reused.
- Prefer controlled props and clear interfaces for reusable components.

## Styling guidelines
- Follow existing styling approach in this repo (`App.css`, `index.css`).
- Keep CSS changes localized and avoid broad global overrides.

## Quality checks before finishing
- Run lint for modified files when possible.
- Ensure TypeScript compiles for affected code paths.
- Keep user-visible behavior and API surface stable unless explicitly requested.

## Response behavior
- Explain what changed and why, briefly.
- Reference updated files.
- If assumptions are needed, state them clearly.
