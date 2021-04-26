<template>
  <section class="home-page">
    <app-hero />
    <app-build />
    <app-reviews />
    <section class="start-action">
      <div class="flex justify-between start-container">
        <h1>Ready to get started?</h1>
        <button class="contact-btn">contact-us</button>
      </div>
    </section>
  </section>
</template>

<script>
import appHero from "@/components/app-hero.vue";
import AppBuild from "@/components/app-build.vue";
import AppReviews from "@/components/app-reviews.vue";
export default {
  components: { appHero, AppBuild, AppReviews },
};
</script>
