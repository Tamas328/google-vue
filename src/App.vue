<template>
  <Header />
  <GoogleLogo />
  <Search />
</template>

<script>
import Header from "./components/Header.vue";
import GoogleLogo from "./components/Logo.vue";
import Search from "./components/Search.vue";

export default {
  name: "App",
  components: {
    Header,
    GoogleLogo,
    Search,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: flex;
  flex-direction: column;
  height: 100%;
}
</style>
