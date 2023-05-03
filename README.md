# Svelte-Kit + PayloadCMS Turborepo

This is an custom made Turborepo starter.

## What's inside?

This [Turborepo] includes the following packages/apps:

### Apps

Each app is 100% [TypeScript].

- `web`: a [Svelte-kit] web app with [UnoCSS] for styling
- `server`: an [Express] app with [PayloadCMS] setup

### Packages

- `eslint-config-custom`: `eslint` configurations (includes `eslint-plugin-svelte` and `eslint-config-prettier`)
- `dum`: a scripts runner executable written in [Rust]
- `replacer`: A CLI for replacing strings in files and directories written in [Rust]

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript] for static type checking
- [ESLint] for code linting
- [Prettier] for code formatting

## Getting Started

This project uses [pnpm].

pnpm install # install dependencies
```

### Running the apps

In the project root and run the following command.

```sh
pnpm dev
```

This will run both the Svelte-kit and Payload apps in parallel.
