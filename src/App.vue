<template>
  <div id="app">
    <MyTitle />
    <MyJumbo />
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import MyJumbo from './components/MyJumbo.vue'


export default {
  name: 'App',
  components: {
    MyTitle,
    MyJumbo
  }
}
</script>

<style lang="scss">

</style>
