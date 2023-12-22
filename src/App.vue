<script setup>
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <router-link to="/">Home</router-link> |
  <router-link to="/about">About</router-link> |
  <router-view></router-view>
</template>
