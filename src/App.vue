<template>
  <body>
    <header>
      <AppTitle />
    </header>

    <main>
      <AppHero />
    </main>
  </body>
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  components: {
    AppTitle, AppHero
  }
}
</script>