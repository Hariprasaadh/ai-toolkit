# Repository Guidelines & Rules

## Project Overview
- **Project**: [Project Name]
- **Core Stack**: [e.g. Next.js 15, TypeScript, TailwindCSS, Supabase]

## Build & Test Commands
- **Install**: `npm install`
- **Dev Server**: `npm run dev`
- **Run Tests**: `npm test`
- **Lint & Format**: `npm run lint`

## Architecture & Code Standards
- **Strict Typing**: Always use strict TypeScript types; avoid `any`.
- **Immutability**: Avoid state mutation; favor spread operators and pure functions.
- **Error Handling**: Never use empty catch blocks. Log structured errors with context.
- **Testing**: Write failing tests before fixing bugs or introducing new features (TDD).

## Agent Invariants
- Do not make breaking API changes without explicit user instructions.
- Ensure all tests pass and linter checks succeed before marking tasks complete.
