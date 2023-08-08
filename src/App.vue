<template>
  <div class="flex flex-col font-Roboto bg-weather-primary min-h-screen">
    <site-navigation/>
    <RouterView />
  </div>
</template>

<script setup>
  import {RouterView} from "vue-router";
import SiteNavigation from "./components/SiteNavigation.vue";
</script>
