<template>
  <div id="app">
    <TabBar>
      <TabBarItem>
        <img solt="item-icon" src="@/assets/img/tabbar/home.svg" alt />
        <div slot="item-text">首页</div>
      </TabBarItem>
      <TabBarItem>
        <img solt="item-icon" src="@/assets/img/tabbar/category.svg" alt />
        <div slot="item-text">分类</div>
      </TabBarItem>
      <TabBarItem>
        <img solt="item-icon" src="@/assets/img/tabbar/cart.svg" alt />
        <div slot="item-text">购物车</div>
      </TabBarItem>
      <TabBarItem>
        <img solt="item-icon" src="@/assets/img/tabbar/profile.svg" alt />
        <div slot="item-text">我的</div>
      </TabBarItem>
    </TabBar>
  </div>
</template>

<script>
import TabBar from "@/components/common/tabbar/TabBar";
import TabBarItem from "@/components/common/tabbar/TabBarItem";
export default {
  name: "App",
  components: {
    TabBar,
    TabBarItem
  }
};
</script>

<style>
/* style里面引入资源需要加入@ */
@import "assets/css/base.css";
</style>
