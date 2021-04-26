<template>
  <section class="app-hero">
    <app-header />
    <img class="img1" src="../assets/images/bg-pattern-home-1.svg" alt="" />
    <img class="img2" src="../assets/images/bg-pattern-home-2.svg" alt="" />
    <div class="flex title">
      <h1 class="header">Find the best <span>talent</span></h1>
      <div class="flex sub-header">
        <div class="rectangle"></div>
        Finding the right people and building high performing teams can be hard.
        Most companies aren’t tapping into the abundance of global talent. We’re
        about to change that.
      </div>
    </div>
  </section>
</template>

<script>
import appHeader from "./app-header.vue";
export default {
  components: { appHeader },
};
</script>

<style>
</style>