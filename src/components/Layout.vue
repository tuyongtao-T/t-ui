<!--
 * @Author: TuYongtao
 * @Date: 2021-11-21 22:28:08
 * @LastEditTime: 2021-11-21 22:47:59
 * @LastEditors: TuYongtao
 * @Description: 
-->
<template>
    <div class="layout">
        <div class="header"></div>
        <div class="main">
            <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
        </div>
        <div class="footer"></div>
    </div>
</template>

<script>
export default {
    name: 'layout',
};
</script>

<style lang="less" scoped>
.layout {
    display: grid;
    grid-template-columns: auto;
    grid-template-rows: 80px auto 60px;
    width: 100%;
    height: 100%;
    .header,.footer {
       background: pink;
    }
    
}
</style>