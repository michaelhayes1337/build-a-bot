<script setup lang="ts">
import { RouterView } from "vue-router";
import HomePage from "./home/HomePage.vue";
import NavbarComponent from "./shared/NavbarComponent.vue";
import RobotBuilder from "./build/RobotBuilder.vue";
</script>

<template>
  <NavbarComponent />
  <HomePage msg="Hello World" />
  <RobotBuilder />
  <RouterView />
</template>

<style>
body {
  background: linear-gradient(to-bottom, #555, #999);
}
main {
  margin: 0 auto;
  padding: 30px;
  background-color: white;
  width: 1024px;
  min-height: 300px;
}
</style>
