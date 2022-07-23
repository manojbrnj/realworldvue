<template>
  <div class="navbar">
    <v-main>
      <router-link :to="{ name: 'about' }">About</router-link>
      <router-link to="/home">Home</router-link>
      <router-view />
    </v-main>
  </div>
</template>
<script>
export default {
  name: "NavBar",
};
</script>
<style lang=""></style>
