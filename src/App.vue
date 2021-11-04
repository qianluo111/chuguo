<template>
  <div id="app">
      <home />
    <!-- <div id="nav">
      
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
  </div>
</template>
<script>
import Home from '../src/views/Home.vue'
export default {
  components:{
      Home
  }
}
</script>
<style lang="scss">
*{margin:0; padding:0;}
 li{list-style: none;}
  html,body,.wrap{
    height: 100%;
  }
  body{
      font-size: .16rem;
  }
</style>
