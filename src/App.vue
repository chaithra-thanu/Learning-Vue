<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="https://vuejs.org/images/logo.png"> -->
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <!-- <h1>Vue</h1>
    <input v-model="message" placeholder="add card" />
    <button>Add card</button> -->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import { ref, isRef, isReactive } from 'vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
  // setup() {
  //   const message = ref('data');
  //   console.log(isRef(message.value));
  //   return {
  //     message,
  //   };
  // },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
