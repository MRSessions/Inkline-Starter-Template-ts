<script setup lang="ts">
import DefaultBar from './NavBar.vue'
import DefaultView from './View.vue'
import DefaultFooter from './Footer.vue'
</script>

<template>
  <i-layout style="height: 100vh">
    <i-layout-header>
      <DefaultBar />
    </i-layout-header>

    <i-layout-content>
      <DefaultView />
    </i-layout-content>

    <i-layout-footer>
      <DefaultFooter />
    </i-layout-footer>
  </i-layout>
</template>