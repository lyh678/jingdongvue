<template>
  <div id="app">
  <v-login></v-login>
  

  </div>
</template>
<script>
import Login from './views/login'

export default {
    name: 'App',
  components: {
    'v-login': Login,
  
  }
}
</script>

<style>

</style>
