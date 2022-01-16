<template>
  <div id="app">
    <h1>黑马头条</h1>
    <div class="test"></div>
    <router-view />
  </div>
</template>
<script>
export default {
  name: 'App',
  data () {
    return {
      value: ''
    }
  }
}
</script>
<style lang="less">
.test {
  width: 150px;
  height: 150px;
  background-color: pink;
}
</style>
