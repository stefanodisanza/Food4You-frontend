<template>
  <Hero />
  <Restaurants id="restaurants" class="stacco " />
</template>
  
<script>

import Restaurants from '../components/Restaurants.vue';
import Hero from '../components/Hero.vue';
export default {
  components: {
    Restaurants,
    Hero,


  }

}
</script>
  
<style scoped>
.stacco {
  padding-top: 150px;
}
</style>