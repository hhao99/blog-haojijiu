# Nuxt 4
Nuxt 4 is the major update on the Nuxt which is not released yet, but you can use some featuer now.

## Summary of the new feature

* Dirctory Structure, the new directory structure was introduced,
* turbo model, with the vite 6 support, increase the development and build speed.
* Native edge server, make Nuxt a more robust option to build web applications.
* Reactivity, file structure and data fetching, it's the new ways to handle these aspects of development.
* Custom prefetch trigger: the new feature you can config with nuxt-link to trigger on visible or on active

Nuxt 4 is refresh version of Nuxt 3 and with some new feature, you can now use it now.

## How to start to use Nuxt 4 feature now
First, you need to upgrade Nuxt 3.12 or later.
Then you set the your compababilityversion to 4 to match Nuxt4 behavior

```ts
export default defineNuxtConfig({
  ...
  future: {
	compatibilityVersion: 4, 
  }
})

```
then we can move all the code to the app directory, then test it.

That's all.


