<template>
  <div id="app">
    <router-view></router-view>
    <mainTabBar></mainTabBar>
  </div>
</template>

<script>
  import mainTabBar from "./components/mainTabBar";
  
  export default {
    name: "App",
    components: {
      mainTabBar
    }
  }

</script>

<style scoped>
  @import "./assets/css/base.css";
</style>
