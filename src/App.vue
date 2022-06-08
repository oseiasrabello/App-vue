<template>
  <NavbarComponents />
  <FooterComponents />
</template>

<script>
import FooterComponents from "./components/Footer/FooterComponents.vue";
import NavbarComponents from "./components/Menu/NavbarComponents.vue";

export default {
  name: "App",
  components: {
    NavbarComponents,
    FooterComponents,
  },
};
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  width: 100%;
  height: 100vh;
  background-color: aliceblue;
}
</style>
