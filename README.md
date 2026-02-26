# ts-package-template

A minimal TypeScript package template with dual CJS/ESM output.

## Features

- TypeScript with strict mode
- Dual CJS/ESM output via [pkgroll](https://github.com/privatenumber/pkgroll)
- [vitest](https://vitest.dev) for testing
- [oxlint](https://oxc.rs/docs/guide/usage/linter) for linting
- [oxfmt](https://oxc.rs/docs/guide/usage/formatter) for formatting
- CI via shared workflows from matt-riley-ci

## Getting started

```bash
pnpm install
pnpm test
pnpm build
```

## Scripts

| Script         | Description              |
| -------------- | ------------------------ |
| `build`        | Build with pkgroll       |
| `test`         | Run tests                |
| `test:watch`   | Run tests in watch mode  |
| `lint`         | Lint with oxlint         |
| `format`       | Format with oxfmt        |
| `format:check` | Check formatting         |
