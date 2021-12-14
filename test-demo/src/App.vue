<template>
  <div id="app">
    <img src="./assets/logo.png" />
    <!-- <Test /> -->
    <CwhButton />
  </div>
</template>

<script>
import { Button as CwhButton } from 'cwh-ui'
import Test from './components/test.vue'

export default {
  name: 'App',
  components: {
    Test,
    CwhButton
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
