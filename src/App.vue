<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    <Navbar />
      
      <v-spacer></v-spacer>
      <div>
        Test
      </div>
  
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
//import HelloWorld from './components/HelloWorld';
import Navbar from './components/Navbar'

export default {
  name: 'App',

  components: {
  //  HelloWorld,
    Navbar
  },

  data: () => ({
    //
  }),
};
</script>
