# OnsenUI Vue Side Splitter Example

Based off of the OnsenUI Vue `<v-ons-splitter-side>` tutorial: https://onsen.io/v2/api/vue/v-ons-splitter-side.html.

This example will move the page components into their own `.vue` files.

This repository demonstrates 3 different methods of implenting the OnsenUI + Vue Side Splitter.

1. The `using-function-property` branch demonstrates the side splitter by using a function as a property of the `side-splitter-content` component.

2. The `vue-router` branch demonstrates the side splitter by using OnsenUI's `vue-router` wrapper.

3. The `vuex` branch demonstrates the side splitter by using VueX to manage the state of the side splitter. The state persists from the menu and the tab bar component.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
