<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>
<template>
  <!-- Här lägger ni en navbar och istället för href så använder ni RouterLink -->
  <ul>
    <li>
      <RouterLink to="/">Hem</RouterLink>
    </li>
    <li>
      <RouterLink to="/about">Lägg till LIA</RouterLink>
    </li>
  </ul>
  <RouterView />
</template>
