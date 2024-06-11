<template>
  <div id="app">
    <TeachersComponent/>
  </div>
</template>

<script>
import TeachersComponent from './components/TeachersComponent.vue'

export default {
  name: 'App',
  components: {
    TeachersComponent,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
