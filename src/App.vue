<script setup>
import NavBar from "./components/NavBar.vue";
import FooterFooter from "./components/FooterFooter.vue";
//import FotterFotter from "./components/FotterFotter.vue";
</script>

<template>
  <NavBar />
  <FooterFooter />
</template>

<style scoped>
@media screen and (min-width: 360px) and (max-width: 980px) {
  body,
  html {
    overflow-x: hidden;
    width: 100%;
    height: auto;
  }
}
</style>
