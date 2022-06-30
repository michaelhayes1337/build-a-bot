<script lang="ts">
import { RouterLink } from "vue-router";
export default {
  name: "NavbarComponent",
};
</script>
<template>
  <header>
    <nav>
      <ul>
        <nav-item>
          <RouterLink to="/"
            ><img src="../assets/build-a-bot-logo.png" alt="logo" class="logo"
          /></RouterLink>
        </nav-item>
        <nav-item>
          <RouterLink to="/">Home</RouterLink>
        </nav-item>
        <nav-item>
          <RouterLink to="/about">About</RouterLink>
        </nav-item>
        <nav-item>
          <RouterLink to="/getstarted">Get Started</RouterLink>
        </nav-item>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
header {
  background-color: #999;
  width: 1084px;
  margin: 0 auto;
}
ul {
  padding: 3px;
  display: flex;
}
.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo {
  vertical-align: middle;
  height: 30px;
}
</style>
