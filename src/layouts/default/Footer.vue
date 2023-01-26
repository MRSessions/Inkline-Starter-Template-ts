<script setup lang="ts">
import IconHeart from './icons/IconHeart.vue'
</script>

<template>
  <i-container fluid class="_position:absolute-bottom" style="background: rgba(0, 0, 0, 0.1);">
    <i-row class="_margin-bottom:0">
      <i-column>
        <div class="_padding-top:1 _display:flex _align-items:center _justify-content:center _flex-wrap:wrap">
          <p>Built with</p>
          <IconHeart />
          <p>By</p> &nbsp;
          <a href="https://github.com/MRSessions" target="_blank" rel="noopener">@MRSessions</a>
        </div>
      </i-column>
    </i-row>
    <i-row>
      <i-column>
        <div class="_padding-bottom:1 _display:flex _align-items:center _justify-content:center _flex-wrap:wrap">
          <p>Copyright © {{ new Date().getFullYear() }}, Inkline TS Starter Template</p>
        </div>
      </i-column>
    </i-row>
  </i-container>
</template>



<style scoped>
p {
  padding: 0;
  margin: 0;
}
</style>