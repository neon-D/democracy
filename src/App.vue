<template>
  <div id="app">
    {{msg}}
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Hello, neon.D!'
    }
  }
}
</script>

<style lang="scss">
body {
    width: 100vw;
    height: 100vh;
    overflow: hidden;
    background-image: url('./assets/bg_normal.jpg');
    background-size: cover;
    background-position: center;
}
</style>
