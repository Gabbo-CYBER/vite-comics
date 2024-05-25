<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import ComicsList from './components/ComicsList.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    ComicsList,
  },
  data() {
    return {
      
    }
  },
  methods: {
   
    }
  }
 
</script>

<template>
  <AppHeader>
     <!-- <a href="google.it">Link non stilizzato in header</a>  -->
  </AppHeader>

  <AppMain>


  </AppMain>

    
  <AppFooter />
      
</template>

<style scoped>

</style>