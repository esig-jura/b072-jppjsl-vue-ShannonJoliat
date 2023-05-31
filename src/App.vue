<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Entete from "@/components/Entete.vue";
import PiedDePage from "@/components/PiedDePage.vue";
</script>

<template>
  <entete></entete>
  <RouterView />
  <PiedDePage></PiedDePage>
</template>

<style scoped>

</style>
