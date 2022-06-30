<script setup lang="ts"></script>

<template>
  <div class="home">
    <div>
      <img class="robot" src="../assets/robot-home.png" alt="robot" />
    </div>
    <div class="get-started">
      <RouterLink to="/getstarted">Get Started</RouterLink>
    </div>
  </div>
</template>

<style scoped>
.home {
  text-align: center;
}
.robot {
  height: 300px;
}
</style>
