<template>
  <div id="app">
    <button><router-link to="/home">首页</router-link></button>
    <router-link to="/about">关于</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>

</style>
