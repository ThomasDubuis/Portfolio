<template>
  <Navbar/>
  <router-view/>
</template>
<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar/Navbar.vue'

export default {
  components: {
    Navbar
  }
}
</script>
<style lang="less">
@import "./styles/global.less";
*{
  color: @color-global-white;
  background-color: @color-global-black;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
}


</style>
