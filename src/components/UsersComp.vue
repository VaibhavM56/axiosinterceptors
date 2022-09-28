<template>
  <h1>User</h1>
</template>

<script>
import { JSONUSERS } from "../axiosConfig";
export default {
  methods: {
    async fetchUsers() {
      let res = await JSONUSERS.get("/users");
      console.log("users res", res);
    },
  },
  mounted() {
    this.fetchUsers();
  },
};
</script>

<style></style>
