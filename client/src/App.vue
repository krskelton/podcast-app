<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Podcasts title="Podcasts"/>
  </div>
</template>

<script>
import Podcasts from './components/Podcasts.vue'

export default {
  name: 'app',
  components: {
    Podcasts
  }
}
</script>

<style>
</style>
