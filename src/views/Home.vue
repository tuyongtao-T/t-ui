<!--
 * @Author: TuYongtao
 * @Date: 2021-11-21 22:10:16
 * @LastEditTime: 2021-11-21 22:25:56
 * @LastEditors: TuYongtao
 * @Description: 
-->
<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/imgs/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
