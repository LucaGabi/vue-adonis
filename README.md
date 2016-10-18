<p align="center"><img height="150" width="390" src="https://raw.githubusercontent.com/atinux/vue-adonis/master/template/resources/src/assets/img/logo.png"></p>

# Adonis-Vue

> AdonisJS + Vue.js = :fire:

## Features

1. Vue.js 2.0 with server-side rendering (+ cacheable components)
2. Hot reloading (via webpack)
3. Configurable via config/vue.js
4. vuex and vue-router are installed and ready to use (synced with vue-router-sync)
5. All the awesome features of AdonisJS

## Installation

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli).

```bash
vue init atinux/vue-adonis <project-name>
cd <project-name> # move to your project
mv .env.example .env # Add environment variables for Adonis
npm install # or yarn install
```

## Usage

### Development

```bash
npm run dev
```

Go to http://localhost:8080

### Production

```
NODE_ENV=production npm start
```

## Documentation

- [AdonisJS](http://adonisjs.com/docs/)
- [Vue.js](http://vuejs.org/guide/)

To understand the `preFetch` method in the matched route components (`resources/src/server-entry.js`), I recommend to look at https://github.com/vuejs/vue-hackernews-2.0

I recommend to use [axios](https://github.com/mzabriskie/axios) for making HTTP request for both client-side and server-side.

Thanks to [Evan You](https://twitter.com/youyuxi), [Aman Virk](https://twitter.com/AmanVirk1) and their awesome communities for creating and maintaining Vue.js and AdonisJS :clap:

## Tests

There is no tests in this template because it's hard to know exactly which tests you will use and even how you want to structure them in this isomorphic application.

Here some ideas:

- [adonis-rally](https://github.com/adonisjs/adonis-rally) project, it has a bunch of tests made by the creator of adonis-framework
- [vue webpack template](https://github.com/vuejs-templates/webpack/tree/master/template) might help you to see how to structure end-to-end and unit test for you web-app

## Licenses

- [AdonisJS license](https://github.com/adonisjs/adonis-framework/blob/develop/LICENSE.txt)
- [VueJS license](https://github.com/vuejs/vue/blob/master/LICENSE)
