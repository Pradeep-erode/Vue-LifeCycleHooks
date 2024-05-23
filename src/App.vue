<template>
<div>
  <lifecycle/>
  <compositionlifecycle/>
</div>
  
</template>

<script>
import lifecycle from './components/lifecyclehooks.vue'
import compositionlifecycle from './components/compositionlifecycle.vue'
export default {
  name: 'App',
  components: {
    lifecycle,compositionlifecycle
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
