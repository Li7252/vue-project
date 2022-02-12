<script>
import AppNavbar from "./components/AppNavbar.vue"
import { RouterView } from 'vue-router'
export default {
  components: {AppNavbar}
}
</script>

<template>
  <app-navbar />
  <RouterView />
</template>

<style>

</style>
