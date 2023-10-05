<template>
  <div id="app">
    <Header />
    <Profile />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Layout/Header.vue";
import Profile from "./components/Profile.vue";
import Footer from "./components/Layout/Footer.vue";
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";

export default {
  name: "app",
  components: {
    Header,
    Profile,
    Footer,
    FontAwesomeIcon
  },
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<style>
body {
  font-family: "Lato", arial, sans-serif;
  color: #434343;
  background: #dae3e7;
  font-size: 16px;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
