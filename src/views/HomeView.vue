<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
// eslint-disable-next-line import/no-unresolved
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
  },
  created() {
    console.log(process.env.VUE_APP_API, process.env.VUE_APP_PATH);
  },
};
</script>
