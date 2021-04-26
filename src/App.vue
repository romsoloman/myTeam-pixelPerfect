<template>
  <div class="app">
    <home-page />
    <app-footer />
  </div>
</template>

<script>
import appFooter from "./components/app-footer.vue";
import HomePage from "./views/home-page.vue";
export default {
  components: { appFooter, HomePage },
};
</script>

<style>
</style>

