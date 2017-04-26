# Vuexpresso

Vuexpresso is a skeleton app that uses the new techs like
 `vue`, `vuex`, `graphql`, `webpack`, `apollo`, between others (See complete list below).

Mainly inspired by

* [Frappe](https://github.com/dweldon/frappe)

# Getting Started

```
git clone https://github.com/Ethaan/vuexpresso.git
yarn
yarn run dev
```

# Other Commands

`yarn run play` - Serves a play server using [vue-play](https://github.com/vue-play/vue-play)

# What includes

### Graphql server

By default it runs a server on `/graphql`, in order to make the API calls, you can delete the part where the server is initialized on `build/dev-server.js` if you have an external API server

### GraphiQL UI
**default** to `/graphiql` but you can change it on `data/base-config.js`;

### Vue-Play UI.

It offers an UI to visualize all the current components of the app, and well.. play with them.

### Vuex Config.

Vuex is already all setup so you can only worry about adding modules, an example can be found here `src/store/modules/notifications.js`;

### Vue Router

Routes live inside `src/routes.js`

### Webpack

Using [Webpack master example](https://github.com/vuejs-templates/webpack/tree/master/template) as reference, with slight modifications to make it work with ES6 and graphql

### Jade & Stylus

You can easy remove Jade and stylus by simply removing them from the tag like `<template lang="jade"></template` => `<template></template` same for stylus.

# Libraries and Technologies used

* [Express](http://expressjs.com/)

* [VueJS](https://vuejs.org/)

* [Vue-Play](https://github.com/vue-play/vue-play)

* [Vuex](https://github.com/vuejs/vuex)

* [Vue-Router](https://github.com/vuejs/vue-router)

* [Vue-Apollo](https://github.com/Akryum/vue-apollo)

* [Apollo-client](http://dev.apollodata.com/)

* [GraphQL](http://facebook.github.io/graphql/)

* [Webpack](https://github.com/webpack/webpack)

* [Pug](https://github.com/pugjs/pug)

* [Stylus](https://github.com/stylus/stylus)

* [Lodash](https://github.com/lodash/lodash)

* [Babel](https://github.com/babel/babel)

* [Mongo](https://github.com/mongodb/mongo)

* [Eslint](https://github.com/eslint/eslint)

TODO

- [ ] Build for Production
