<template>
  <v-app >
    <v-main>
      <router-view />
    </v-main>

    <AppFooter />
  </v-app>
</template>

<script setup>
  import DefaultBar from './AppBar.vue'
  import DefaultView from './View.vue'
  //
</script>
