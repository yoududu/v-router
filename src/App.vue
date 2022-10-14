<template>
  <div id="app">
    <router-link to="/">首页</router-link>
    <router-link to="/hello">详情页</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
// 路由对应组件渲染
// 路由自检需要用 vue-router提供的router-view组件来渲染
export default {
  name: 'App',
}
</script>

<style>
</style>
