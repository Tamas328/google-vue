<template>
  <div class="main">
    <Header />
    <GoogleLogo />
    <Search />
    <Alts />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import GoogleLogo from "./components/Logo.vue";
import Search from "./components/Search.vue";
import Alts from "./components/Alts.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "Main",
  components: {
    Header,
    GoogleLogo,
    Search,
    Alts,
    Footer,
  },
};
</script>

<style scoped>
.main {
  display: flex;
  flex-direction: column;
  height: 100%;
}
</style>
