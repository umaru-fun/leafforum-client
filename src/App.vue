<template>
  <div id="app">
    <Header></Header>
    <router-view></router-view>
  </div>
</template>


<script>
import Header from 'components/Header/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>

</style>
