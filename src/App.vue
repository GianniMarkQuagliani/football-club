<template>
  <HelloWorld />
  <Test />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Test from './components/Partials/Test.vue';
export default {
  name: 'App',
  components: {
    HelloWorld,
    Test
  }
}
</script>

<style lang="scss" scoped>
@use "./assets/scss/main.scss";

</style>