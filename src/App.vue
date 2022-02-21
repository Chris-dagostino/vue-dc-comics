<template>
  <div id="app">
    <MyHeader></MyHeader>
    <MyMain></MyMain>
    <MyFooter></MyFooter>
    
    
  </div>
</template>

<script>
import MyMain from './components/MyMain.vue';
import MyFooter from './components/MyFooter.vue';
import MyHeader from './components/MyHeader.vue';

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter
  }
}
</script>

<style lang="scss">
#app {
 
}
</style>
