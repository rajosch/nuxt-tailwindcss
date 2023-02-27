# Fast setup for tailwindcss using Nuxt 3

Just install the layer and start using tailwindcss with Nuxt 3.

## Install

Make sure to install the dependencies:

```bash
npm install @nuxtjs/tailwindcss nuxt-tailwindcss
```

## nuxt.config.ts

```ts
defineNuxtConfig({
  extends: [
    'nuxt-tailwindcss'
  ],
  modules: [
    '@nuxtjs/tailwindcss'
  ]
})
```



