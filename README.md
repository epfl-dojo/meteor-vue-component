# Vue as a Meteor UI layer

[![meteor](https://img.shields.io/badge/meteor-1.4.2.3-blue.svg)](https://meteor.com/)
[![vue1](https://img.shields.io/badge/vue-1.x-green.svg) ![vue2](https://img.shields.io/badge/vue-2.x-brightgreen.svg)](https://vuejs.org/)

**This project is in beta.**

This project contains new meteor packages to help build [meteor](http://meteor.com/) apps with first-class [vuejs](http://vuejs.org/) integration as the ui layer.

## Examples

- [Simple example project](https://github.com/Akryum/meteor-vue-example)
- [Simple example project (Vue 2.x)](https://github.com/Akryum/meteor-vue2-example)
- [Blaze example project](https://github.com/Akryum/meteor-vue-blaze) [[2](https://github.com/Akryum/meteor-vue-blaze/tree/render-blaze)]
- [Routing example project](https://github.com/Akryum/meteor-vue-example-routing)
- [Routing example project (vue 2.x)](https://github.com/Akryum/meteor-vue2-example-routing)
- [i18n example project](https://github.com/Akryum/meteor-vue-example-i18n)
- [Vuex example project](https://github.com/Akryum/meteor-vuex-example)

## Features

Currently supported and possible future features (in no particular order) are:

 - [x] Declarative subscriptions and meteor reactive data ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] Single-file components (.vue) with basic support of `<template>`, `<script>` and `<style>` (with optional `scoped` attribute) ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] Instant Hot-reloading of components ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] `lang` attribute on `<style>` in .vue files ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] Less official integration in .vue files ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] Sass official integration in .vue files ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] Stylus official integration in .vue files ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] `lang` attribute on `<template>` in .vue files ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] Jade official integration in .vue file ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] `lang` attribute on `<script>` in .vue files ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] Coffeescript official integration in .vue files ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] Apollo client integration ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] Easy routing with vue-router out-of-the-box integration & fast-render ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [x] Easy localization with vue-i18n out-of-the-box integration, auto-detection, server-side injection and key-in-hand ui ![vue](https://img.shields.io/badge/vue-1.x-green.svg)
 - [x] Easy state management with vuex integration ![vue](https://img.shields.io/badge/vue-1.x-green.svg)
 - [x] Use Blaze templates in your vue app ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)
 - [ ] *Typescript official integration in .vue files*
 - [ ] *Server-side rendering (Vue 2.x)*

Track the project progress [here](https://github.com/Akryum/meteor-vue-component/milestones).

## Usage

### New project without blaze

See the [simple example project](https://github.com/Akryum/meteor-vue-example).

### New project with blaze

See the [blaze example project](https://github.com/Akryum/meteor-vue-blaze).

### Development project

Clone this repository and type in the project directory:

    meteor npm install
    meteor

### Meteor & Tracker data integration ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)

Declarative subscriptions and meteor reactive data

[See Usage in akryum:vue package](https://github.com/Akryum/meteor-vue-component/tree/master/packages/vue#usage)

### Single-file component ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)

It allows you to write your components in [this format](https://vuejs.org/guide/application.html#Single-File-Components) with hot-reloading support.

[See Usage in arkyum:vue-component package](https://github.com/Akryum/meteor-vue-component/tree/master/packages/vue-component#usage)

### Routing

#### ![vue](https://img.shields.io/badge/vue-1.x-green.svg)

Routing for Vue 1.x and Meteor using [vue-router](https://github.com/vuejs/vue-router).

[See Installation & Usage in arkyum:vue-router package](https://github.com/Akryum/meteor-vue-component/tree/master/packages/vue-router#installation)

[Example app](https://github.com/Akryum/meteor-vue-example-routing)

#### ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)

Routing for Vue 2.x and Meteor using [vue-router](https://github.com/vuejs/vue-router).

[See Installation & Usage in arkyum:vue-router2 package](https://github.com/Akryum/meteor-vue-component/tree/master/packages/vue-router2#installation)

[Example app](https://github.com/Akryum/meteor-vue2-example-routing)

### Apollo integration ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)

Use apollo in your vue component!

[See Installation & Usage in the vue-apollo npm package](https://github.com/Akryum/vue-apollo)

### Localization ![vue](https://img.shields.io/badge/vue-1.x-green.svg)

Translate your app quickly and easily with [vue-i18n](https://github.com/kazupon/vue-i18n).

[See Installation & Usage in akryum:vue-i18n package](https://github.com/Akryum/meteor-vue-component/tree/master/packages/vue-i18n#installation)

[Premade selection ui in akryum:vue-i18n-ui package](https://github.com/Akryum/meteor-vue-component/tree/master/packages/vue-i18n-ui)

[Example app](https://github.com/Akryum/meteor-vue-example-i18n)

### State management with vuex ![vue](https://img.shields.io/badge/vue-1.x-green.svg)

Manage the state of your app with a centralized data store with [vuex](https://github.com/vuejs/vuex).

[See Installation & Usage in akryum:vuex](https://github.com/Akryum/meteor-vue-component/tree/master/packages/vuex#installation)

[Example app](https://github.com/Akryum/meteor-vuex-example)

### Embed Blaze template ![vue](https://img.shields.io/badge/vue-1.x-green.svg) ![vue](https://img.shields.io/badge/vue-2.x-brightgreen.svg)

Use Blaze templates inside your vue components.

[See Installation & Usage in akryum:vue-blaze-template](https://github.com/Akryum/meteor-vue-component/tree/master/packages/vue-blaze-template)

[Example app](https://github.com/Akryum/meteor-vue-blaze/tree/render-blaze)

## Get involved

This project is very much a work-in-progress, so your help will be greatly appreciated!  
Feel free to contribute by opening a PR or an issue (but check before if the topic already exists).

---

LICENCE ISC - Created by Guillaume CHAU (@Akryum)
