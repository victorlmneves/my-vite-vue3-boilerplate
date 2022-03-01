# Vue 3 + Typescript + Vite
[![Updated Badge](https://badges.pufler.dev/updated/victorlmneves/vue3-vite-boilerplate)](https://badges.pufler.dev) [![Created Badge](https://badges.pufler.dev/created/victorlmneves/vue3-vite-boilerplate)](https://badges.pufler.dev) [![Commits Badge](https://badges.pufler.dev/commits/monthly/victorlmneves)](https://badges.pufler.dev) [![Visits Badge](https://badges.pufler.dev/visits/victorlmneves/vue3-vite-boilerplate)](https://badges.pufler.dev)

<p align='center'>
  <img src='https://avatars.githubusercontent.com/u/17341789?v=4' alt='Victor Neves - Frontend developer' width='460'/>
</p>

<p align='center'>
Vue 3 with TS and Vite boilerplate<br>
</p>

<br>

## Features

- ⚡️ [Vue 3](https://github.com/vuejs/vue-next), [Vite](https://github.com/vitejs/vite), [TypeScript](https://github.com/microsoft/TypeScript), [Pinia](https://github.com/vuejs/pinia), [PostCSS](https://github.com/postcss/postcss), and [Snyk](https://github.com/snyk/snyk)

- 🍍 [State Management via Pinia](https://pinia.esm.dev/)

- 📲 [PWA](https://github.com/antfu/vite-plugin-pwa)

- 🔥 Use the [new `<script setup>` syntax](https://github.com/vuejs/rfcs/pull/227)

- 🦾 TypeScript

- ⚙️ Unit Testing with [Vitest](https://github.com/vitest-dev/vitest), E2E Testing with [Cypress](https://cypress.io)

- ☁️ Deploy on [Netlify](https://www.netlify.com), zero-config

<br>

## Pre-packed

### Plugins

- [Vue Router](https://github.com/vuejs/vue-router)
- [Pinia](https://pinia.esm.dev) - Intuitive, type safe, light and flexible Store for Vue using the composition api
- [`vite-plugin-pwa`](https://github.com/antfu/vite-plugin-pwa) - PWA

### Coding Style

- Use Composition API with [`<script setup>` SFC syntax](https://github.com/vuejs/rfcs/pull/227)
- [ESLint](https://eslint.org/) with single quotes, no semi.

### Dev tools

- [TypeScript](https://www.typescriptlang.org/)
- [Vitest](https://github.com/vitest-dev/vitest) - Unit testing
- [Cypress](https://cypress.io/) - E2E testing
- [Netlify](https://www.netlify.com/) - zero-config deployment
- [VS Code Extensions](./.vscode/extensions.json)
  - [Vite](https://marketplace.visualstudio.com/items?itemName=antfu.vite) - Fire up Vite server automatically
  - [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) - Vue 3 `<script setup>` IDE support
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

## Variations

This version uses [Vitest](https://github.com/vitest-dev/vitest) for unit tests. If you prefer I have a [version](https://github.com/victorlmneves/vue3-vite-boilerplate) using [Jest](https://github.com/facebook/jest) for unit tests.

## Usage

### Development

Just run and visit http://localhost:3000

```bash
pnpm dev / yarn dev / npm run dev
```

### Build

To build the App, run

```bash
pnpm build / yarn build / npm run build
```

And you will see the generated file in `dist` that ready to be served.

### Preview build

To preview the App build, run

```bash
pnpm preview / yarn preview / npm run preview
```

### Storybook

To execute and preview Storybook, run

```bash
pnpm storybook / yarn storybook / npm run storybook
```

### Storybook build

To build Storybook, run

```bash
pnpm build-storybook / yarn build-storybook / npm run build-storybook
```

### Unit tests

To execute the unit test, run

```bash
pnpm test:unit / yarn test:unit / npm run test:unit
```

### E2E tests

To execute the E2E tests, run

```bash
pnpm test:e2e / yarn test:e2e / npm run test:e2e
```

### Unit tests coverage report

To generate the HTML coverage report, run

```bash
pnpm coverare / yarn coverare / npm run coverare
```

### Deploy on Netlify

Go to [Netlify](https://app.netlify.com/start) and select your clone, `OK` along the way, and your App will be live in a minute.

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar)

## Type Support For `.vue` Imports in TS

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type by default. In most cases this is fine if you don't really care about component prop types outside of templates. However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using manual `h(...)` calls), you can enable Volar's `.vue` type support plugin by running `Volar: Switch TS Plugin on/off` from VSCode command palette.
