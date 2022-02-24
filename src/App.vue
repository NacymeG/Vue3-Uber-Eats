<template>
  <!-- <RestaurantRow v-for="(card, index) in 3" :key="index" /> -->
  <HomePage />
</template>

<script>
import HomePage from './pages/HomePage.vue';

export default {
  name: 'App',
  components: { HomePage },
};
</script>

<style>
@import url('./style/reset.css');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');
#app {
  font-family: 'Roboto', 'sans-serif';
}
</style>
