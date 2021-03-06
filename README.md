# Vue 3 Realword app with Server Side Sendering (SSR)

> :shit: coded version of [original repo](https://github.com/mutoe/vue3-realworld-example-app) with working SSR, made with :heart:

This is an experiment with a try to make _normal_ (at least working) SSR. Don't perceive the code as production-ready.  
If you know how to make things better, PRs are welcome

## Getting started

```shell script
git clone https://github.com/levchak0910/vue3-ssr-realworld-example-app.git
cd vue3-ssr-realworld-example-app
yarn install
yarn build-production
yarn serve-production
```

### For development
```shell script
yarn build
yarn serve
```

## Acknowledges

- [@mutoe](https://github.com/mutoe) and [contributors](https://github.com/mutoe/vue3-realworld-example-app#contributors) - for original repo
- [@andrewcourtice](https://github.com/andrewcourtice) - for [state manager](https://github.com/andrewcourtice/harlem) with [ssr support](https://github.com/andrewcourtice/harlem/blob/main/plugins/ssr)
- [@tbgse](https://github.com/tbgse) - for [example](https://github.com/tbgse/vue3-vite-ssr-example) how to use vite for creating ssr bundles

## Vue related implementations of the Realworld app
[gothinkster/vue-realworld-example-app](https://github.com/gothinkster/vue-realworld-example-app) - vue2, js  
[AlexBrohshtut/vue-ts-realworld-app](https://github.com/AlexBrohshtut/vue-ts-realworld-app) - vue2, ts, class-component  
[devJang/nuxt-realworld](https://github.com/devJang/nuxt-realworld) - nuxt, ts, composition api  
[mutoe/vue3-realworld-example-app](https://github.com/mutoe/vue3-realworld-example-app) - vue3, vite, ts, composition api  
