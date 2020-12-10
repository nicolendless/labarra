<template>
  <div class="home">
    <img class="logo" alt="Vue logo" src="../assets/labarra.jpeg">
    <HelloWorld msg="Benvinguts a La Barra"/>
  </div>
</template>

<style>
  .logo {
    width: 600px;
    height: 600px;
  }
</style>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
