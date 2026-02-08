# CLAUDE.md

Gives AI assistants access to Apple Photos -- browse albums, search by keyword, and export images. Built on AppleScript.

## Stack

- TypeScript / Node >=18 / ESM
- MCP SDK, Vitest, ESLint 9, Prettier

## Commands

```sh
npm run build         # tsc
npm test              # vitest run
npm run lint          # eslint src/
npm run lint:fix      # eslint src/ --fix
npm run format:check  # prettier --check .
```

## Conventions

- Server implementation: `src/index.ts`; tests: `src/__tests__/`
- Husky + lint-staged handle pre-commit formatting and linting
