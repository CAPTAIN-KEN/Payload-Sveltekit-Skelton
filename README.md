# Payload CMS - SvelteKit - Skeleton - Turborepo

This is an custom made Turborepo starter.

## What's inside?

This [Turborepo] includes the following packages/apps:

### Apps

Each app is 100% [TypeScript].

- `web`: a [Svelte-kit] web app with [Tailwind] for styling
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

1) Install pnpm -  brew install pnpm
2) Clone the repo 
3) update the .env file with (1) mongo DB connection and (2) payload secret
4) pnpm install // to install dependencies 
5) pnpm dev // to start the server 
6) Payload backend URL = http://localhost:3000/admin
7) Sveltekit / skelton front end URL = http://localhost:5173/

This will run both the Svelte-kit and Payload apps in parallel.
