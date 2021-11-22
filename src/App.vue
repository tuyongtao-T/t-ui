<!--
 * @Author: TuYongtao
 * @Date: 2021-11-21 22:10:16
 * @LastEditTime: 2021-11-21 22:43:36
 * @LastEditors: TuYongtao
 * @Description: 
-->
<template>
  <div id="app">
      <layout></layout>
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/> -->
  </div>
</template>
<script>
import Layout from './components/Layout.vue'
export default {
  components: {
    Layout
  }
}
</script>

<style lang="less">
@import url('./assets/CSS/init.css');
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
