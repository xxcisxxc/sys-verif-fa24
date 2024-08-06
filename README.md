# Systems verification Fall 2024 course website

[![deploy](https://github.com/tchajed/sys-verif-fa24/actions/workflows/deploy.yml/badge.svg)](https://github.com/tchajed/sys-verif-fa24/actions/workflows/deploy.yml)

[Deployed site](https://tchajed.github.io/sys-verif-fa24/)

Run a dev server: `pnpm docs:dev`

Build static site: `pnpm docs:build`

Tech stack:

- pnpm
- [VuePress 2](https://vuepress.vuejs.org/)
  - Using the [VuePress Hope theme](https://theme-hope.vuejs.press/) (rather than the default)
  - Pretty much the whole setup is at [config.ts](docs/.vuepress/config.ts)
- Build and deploy via GitHub Pages [workflow](./.github/workflows/deploy.yml)
