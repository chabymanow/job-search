<template>
  <MainNav />
  <h1 class="text-9xs mt-1 text-ellipsis">Chaby Manow</h1>
  <img alt="Vue logo" src="@/assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";
import MainNav from "@/components/MainNav.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    MainNav,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #064f99;
  margin-top: 60px;
}
</style>
