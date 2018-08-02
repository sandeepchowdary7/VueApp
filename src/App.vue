<template>
  <div id="app">
     <message>Welcome to My Vue App</message>
     <message>Presenting by Vue-World</message>
  </div>
</template>

<script>
import Message  from './components/Message.vue';
export default {
  name: 'app',
  components: { Message },
  data () {
    return {   }
  }
}
</script>

<style lang="scss">

</style>
