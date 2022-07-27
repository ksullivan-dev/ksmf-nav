<template>
  <div style="padding: 32px; outline: 1px solid red">
    <AppNavigation />
  </div>
</template>

<script>
  import AppNavigation from "@/components/AppNavigation.vue";

  export default {
    name: "App",
    components: {
      AppNavigation,
    },
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
