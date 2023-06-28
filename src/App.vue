<script>
import AppTitle from './AppTitle.vue';
import AppHero from './AppHero.vue';
export default {
  components: {
    AppHero,
    AppTitle,
  }
}
</script>

<template>
  <div class="container">
    <main>
      <AppTitle />
      <AppHero />
    </main>
  </div>
</template>

<style>
/* CSS RESET */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Container */
.container {
  max-width: 1000px;
  margin: 0 auto;
  text-align: center;
}
</style>