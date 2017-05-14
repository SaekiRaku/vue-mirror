<template>
  <div>
    <p>Hello World</p>
    <slot>
    </slot>
  </div>
<template>

<style lang="less" scoped>
  div {
    background:#03A9F4;
  }
</style>

<script>
  export default {
    data(){
      return {
        temp:0;
      }
    }
  }
</script>
