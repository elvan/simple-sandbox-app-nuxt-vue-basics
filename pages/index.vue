<template>
  <section class="container">
    <div>
      <logo />
      <h1 class="title">simple-sandbox</h1>
      <h2 class="subtitle">Nuxt.js Sandbox Application</h2>
    </div>
  </section>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo,
  },
};
</script>

<style>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  text-align: center;
}
.title {
  display: block;
  color: #35495e;
  font-weight: 300;
  font-size: 100px;
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  letter-spacing: 1px;
}
.subtitle {
  padding-bottom: 15px;
  color: #526488;
  font-weight: 300;
  font-size: 42px;
  word-spacing: 5px;
}
.links {
  padding-top: 15px;
}
</style>
