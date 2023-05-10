<template>
  <div class="home">
    <a rel="stylesheet" href="AboutView.vue"><img alt="Vue logo" src="../assets/skull.png"></a>
    <HelloWorld msg="Welcome to My Owner!"/>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style>
.home{
  text-align: center;
}


</style>