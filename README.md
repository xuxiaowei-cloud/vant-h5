## 项目创建

1. init

```shell
npm create vite@latest vant-h5 -- --template vue-ts
npm i vant@4.0.0-alpha.4
npm i unplugin-vue-components -D
npm i eslint -D
npx eslint --init
# 选择
# To check syntax, find problems, and enforce code style
# JavaScript modules (import/export)
# Vue.js
# use TypeScript
# √ Browser
# Use a popular style guide
# Standard: https://github.com/standard/standard
# JavaScript
npm i axios
npm i crypto-js
npm i js-cookie
npm i jsencrypt
npm i sockjs-client
npm i stompjs
npm i vue-clipboard3
npm i vue-router
npm i vuex
```

## 文档

- [vant-contrib](https://vant-contrib.gitee.io/vant/v4)
- [vue cli](https://cli.vuejs.org/zh/guide)

# Vue 3 + TypeScript + Vite

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue
3 `<script setup>` SFCs, check out
the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)

## Type Support For `.vue` Imports in TS

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type
by default. In most cases this is fine if you don't really care about component prop types outside of templates.
However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using
manual `h(...)` calls), you can enable Volar's Take Over mode by following these steps:

1. Run `Extensions: Show Built-in Extensions` from VS Code's command palette, look
   for `TypeScript and JavaScript Language Features`, then right click and select `Disable (Workspace)`. By default,
   Take Over mode will enable itself if the default TypeScript extension is disabled.
2. Reload the VS Code window by running `Developer: Reload Window` from the command palette.

You can learn more about Take Over mode [here](https://github.com/johnsoncodehk/volar/discussions/471).

## Stargazers over time

[![Stargazers over time](https://starchart.cc/xuxiaowei-cloud/vant-h5.svg)](https://starchart.cc/xuxiaowei-cloud/vant-h5)
