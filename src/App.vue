<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <v-app>
    <Header />
    <div class="content">
      <RouterView />
    </div>
    <Footer />
  </v-app>
</template>

<style scoped>
.content {
  padding-top: 120px;
}
</style>
