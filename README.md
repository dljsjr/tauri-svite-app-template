# Tauri App Template: Svite (Svelte + Vite) && TypeScript in Tauri!

This is a simple skeleton app that provides an environment with:

- [svite](https://github.com/dominikg/svite): Svelte 3 + Vite
  - [Svelte](https://svelte.dev)
  - [Vite](https://github.com/vitejs/vite): Super fast native-ESM powered web dev build tool.
- Configured for TypeScript + SCSS via `node-sass`
- Prettier and ESLint, good to go
- [Tauri](https://tauri.studio): A Rust-backed app framework that uses the system's webview API, making it much lighter than Electron

## Getting Started

### Dev Environment Dependencies

- `yarn` (or `npm` if preferred, but this template provides a `yarn.lock` package lock file)
- A working Rust dev environment: Easiest way to get started is with [rustup](https://rustup.rs)
- After installing Rust, you need to [set up Tauri for your system](https://tauri.studio/en/docs/getting-started/intro)
  - You do not need to `yarn tauri init`, the config files are already generated and in version control, but you can do so if you'd like to overwrite any of the Tauri configs

Once this is all set up, run `yarn` to install all required node packages.

### Starting the app

You will need two terminals.

In the first terminal:

```bash
$ yarn dev
```

and in the second terminal:

```bash
yarn tauri dev
```

You should now have the dev server and dev app window up and ready to go!
