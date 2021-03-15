<template>
  <div>
    Caro
    <v-carousel>
      <v-carousel-item
        v-for="(item,i) in items"
        :key="i"
        :src="item.src"
        reverse-transition="fade-transition"
        transition="fade-transition"
      ></v-carousel-item>
    </v-carousel>
 
  </div>
</template>



<script>
//import Navbar from '../components/Navbar'

export default {
  components: {
 //   Navbar
  },
   data () {
      return {
        items: [
          {
            src: require('../assets/vibe.gif'),
          },
          {
            src: require('../assets/dogcar.gif'),
          },
          {
            src: require('../assets/logo.png'),
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
          },
        ],
      }
    },
};
</script>