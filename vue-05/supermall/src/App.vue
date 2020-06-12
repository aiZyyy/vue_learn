<template>
  <div id="app">
    <router-view></router-view>
    <main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
import MainTabBar from 'content/mainTabbar/MainTabBar'
export default {
  name: "App",
  components: {
    MainTabBar
  }
};
</script>

<style>
/* style里面引入资源需要加入@ */
@import "assets/css/base.css";
</style>
