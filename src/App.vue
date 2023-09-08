<script setup>
import Header from './components/Layout/Header.vue'
import Hero from './components/Hero.vue'
</script>

<template>
  <div class="container">
    <Header />
    <Hero />
  </div>
</template>

<style lang="scss">
@import url('https://fonts.cdnfonts.com/css/satoshi');
@import url('https://fonts.cdnfonts.com/css/overused-grotesk');

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
  font-family: 'Satoshi', sans-serif;
  font-size: 16px;
  // font-family: 'Overused Grotesk', sans-serif;
}

.container {
  max-width: 1440px;
  margin: auto;
}
</style>
