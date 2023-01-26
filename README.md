# Inkline Starter Template (TypeScript)

[Link to the JavaScript version of this project.](https://github.com/MRSessions/Inkline-Starter-Template)

This template should help get you started developing with Vue 3 in Vite using Inkline UI and TypeScript.

A ~~very underwhelming~~ demo can be found [here](https://green-mushroom-01320b310.2.azurestaticapps.net/)! (JavaScript version)

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## About

I decided to create this template to be able to get up and running with Inkline UI quickly. Inkline was something new that I wanted to try out in a quick side project, and I decided that I wanted a blank starter template to start with.

This should have everything to need to start creating a web app from scratch.

- This template is created with TypeScript support out of the box
- Pinia is not included
- Using Vue Composition API using `<script setup>`
- Vue Router is installed using a layout template with a header, content, and footer section
- Mobile friendly
- Color mode is based on system with a toggle to change in the navbar

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
   1. Run `Extensions: Show Built-in Extensions` from VSCode's command palette
   2. Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```
