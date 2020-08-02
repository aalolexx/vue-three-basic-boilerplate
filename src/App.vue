<template>
  <div id="app">
    <Scene/>
  </div>
</template>

<script>
import Scene from './components/Scene.vue'

export default {
  name: 'App',
  components: {
    Scene
  }
}
</script>

<style lang="scss">
@import '/assets/style/custom.scss';
</style>