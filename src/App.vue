// I believe eslint has a problem with my code but i dont want to turn it off.
<template>
  <div>
    <UserInfo />
    <RouterView />
  </div>
</template>

<script setup>
import { RouterView } from "vue-router";
import UserInfo from './components/UserInfo.vue'
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Roboto+Condensed");
html,
body {
  font-family: "Roboto", sans-serif;
}
#app {
  font-family: "Roboto", sans-serif;
}
</style>