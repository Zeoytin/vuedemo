<template>
  <div id="vue">Hello Vue.js! {{ message }}</div>
</template>

<script>
  export default {
    name: 'hello',
    data () {
      return {
        message: 'zyt is coming!!!'
      }
    }
  }
</script>

<style type="text/css">
  #vue {
    color: green;
    font-size: 28px;
  }
</style>
