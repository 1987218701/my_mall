<template>
  <tab-bar>
    <tab-bar-item path="/home">
      <img slot="item-icon" src="~@/assets/img/tabbar/home.png" alt="">
      <img slot="item-icon-active" src="~@/assets/img/tabbar/home-act.png" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/classify">
      <img slot="item-icon" src="~@/assets/img/tabbar/classify.png" alt="">
      <img slot="item-icon-active" src="~@/assets/img/tabbar/classify-act.png" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/shopcart">
      <img slot="item-icon" src="~@/assets/img/tabbar/shopcar.png" alt="">
      <img slot="item-icon-active" src="~@/assets/img/tabbar/shopcar-act.png" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile">
      <img slot="item-icon" src="~@/assets/img/tabbar/profiles.png" alt="">
      <img slot="item-icon-active" src="~@/assets/img/tabbar/profiles-act.png" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from "@/components/tabbar/TabBar";
  import TabBarItem from "@/components/tabbar/TabBarItem";
  
  export default {
    name: "mainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>

</style>