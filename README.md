![Astro Starter](src/assets/logo.png 'Astro Starter')

# Astro Starter

[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard--ext-05ae89.svg)](https://github.com/tinchoz49/eslint-config-standard-ext)
[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/tinchoz49/astro-starter/tree/main)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/tinchoz49/astro-starter/tree/main)

## About

This is an starter Astro project with:

1. astro files are being lint and format with the [Anthony's ESLint config preset](https://github.com/antfu/eslint-config)
1. tailwind support
1. vitest support

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run check`           | Check your project for errors                    |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
| `npm run fix`             | Format with ESLint                               |
| `npm run lint`            | Lint files with standard                         |
| `npm test`                | Run your tests with vitest                       |
