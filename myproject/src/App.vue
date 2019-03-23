<template>
  <div id="app">
    <div class="grid-container-dashboard">
     
      <Main/>
      <Aside/>
      <Footer/>
    </div>
    <!-- <router-view /> -->
  </div>
</template>

<script>
import Main from './components/Main.vue';
import Aside from './components/Aside.vue';
import Footer from './components/HelloWorld.vue';
export default {
  name: 'App',
  components:{
    Main,
    Aside,
    Footer
  }
}
</script>

<style lng="scss" scoped>
  @import './scss/_style.scss';
</style>
