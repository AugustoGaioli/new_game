<template>
  <v-app>
    <v-main>
      
      <LogIn/>
      <MainPage/>
     
    </v-main>
  </v-app>
</template>

<script>



import LogIn from './components/LogIn.vue'
import MainPage from './components/MainPage.vue'

export default {
  name: 'App',

  components: {
    LogIn,
    MainPage
    
},

  data: () => ({
    //
  }),
}
</script>
