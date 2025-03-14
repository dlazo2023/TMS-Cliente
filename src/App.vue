<script setup lang="ts">
  import { RouterLink, RouterView } from "vue-router";
  import Header from "@/components/Header.vue";
  import Footer from "@/components/Footer.vue";
</script>

<template>
  <div id="app" class="full">
    <Header />
    <!-- Resto de tu aplicación -->
    <RouterView />
    <!-- Footer -->
    <Footer />
  </div>
</template>

<style scoped>
  .full {
    height: 100%;
  }
</style>
