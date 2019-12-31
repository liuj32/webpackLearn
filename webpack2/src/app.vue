<template>
  <div id="container">
    <h1>{{ initData }}</h1>
  </div>
</template>

<script>
export default {
  data(){
    return {
      initData: 'Vue 开发环境初始化'
    }
  }
}
</script>

<style >
  .container{
    color: red;
    transform: translateX(20);
  }
</style>