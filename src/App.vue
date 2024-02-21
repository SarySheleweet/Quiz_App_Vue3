<script setup>
import QuizesView from './views/QuizesView.vue'
import { RouterView } from 'vue-router';
</script>

<template>
  <div class="container">
    <RouterView></RouterView>
    <!-- <QuizesView></QuizesView> -->
  </div>
</template>

<style scoped>
.container {
  max-width: 1000px;
  margin: 0 auto;
}
</style>