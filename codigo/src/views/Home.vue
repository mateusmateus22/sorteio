<template>
  <div class="home">
    <HelloWorld msg="Bem-Vindo ao App de sorteios!"/>
  </div>
</template>

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
