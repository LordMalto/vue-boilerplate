<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import AppFooter from "@/components/AppFooter.vue";
</script>

<template>
  <head>
    <title>VueJS Boilerplate</title>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="description" content="VueJS Boilerplate" />
    <meta name="keywords" content="vuejs, vue, vue3, boilerplate, tailwind, tailwindcss, supabase, auth" />
    <meta name="author" content="Malte S" />
    <link rel="icon" href="./assets/logo.svg" />
  </head>
  <RouterView />
  <AppFooter />
</template>
<style scoped>
</style>
