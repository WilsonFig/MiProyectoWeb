<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <NuevoComponente></NuevoComponente>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import NuevoComponente from '@/components/NuevoComponente.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld, NuevoComponente
  }
}
</script>
