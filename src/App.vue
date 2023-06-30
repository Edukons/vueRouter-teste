<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <aside>
    <nav class="menu">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </nav>
  </aside>
  <main>
    <router-view/>
  </main>
  <footer>FOOTER</footer>
</template>

<style scoped>
body{
  background: url("https://img.olhardigital.com.br/wp-content/uploads/2023/03/Star-Wars.jpg");
}
</style>
