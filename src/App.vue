<script setup lang="ts">
import { RouterView } from 'vue-router'
import HeaderPage from './components/HeaderPage.vue';
import FooterPage from './components/FooterPage.vue';

</script>

<template>
  <header>
    <HeaderPage />
  </header>

  <Suspense>
    <RouterView />
  </Suspense>

  <footer>
    <FooterPage />
  </footer>
</template>