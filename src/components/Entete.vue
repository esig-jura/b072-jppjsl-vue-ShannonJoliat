<script setup>

</script>

<template>
<header>
<router-link active-class="actif" to="/">
    <img class="logo" src="_sources/img/logo-jppjsl.png" alt="logo de jppjsl">
</router-link>
  <nav>
      <ul>
          <li>
              <router-link to="/service-client" exact-active-class="actif">Service client</router-link>
          </li>
          <li>
              <router-link to="/sabre/:id" exact-active-class="actif">No sabres</router-link>
          </li>
      </ul>
  </nav>
</header>
</template>

<style scoped>

</style>