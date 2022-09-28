<template>
  <users-comp />
</template>

<script>
import UsersComp from "./components/UsersComp.vue";

export default {
  name: "App",
  components: {
    UsersComp,
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
