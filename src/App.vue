<template>
  <the-header title="Remember Me"></the-header>
  <the-resources></the-resources>
</template>

<script>
import TheResources from "./components/learning-resources/TheResources.vue";
import TheHeader from "./components/layouts/TheHeader.vue";

export default {
  components: {
    TheHeader,
    TheResources,
  },
  data() {
    return {};
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}
html {
  font-family: "Roboto", sans-serif;
}
body {
  margin: 0;
}
</style>
