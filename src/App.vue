<script setup lang="ts">
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'

</script>

<template>
  <div class="flex flex-col p-2">
    <div class="flex flex-row items-center justify-center">
      <img src="/tauri.svg" class="w-20 h-20 logo tauri" alt="Tauri logo" />
      <img src="/vue.svg" class="w-20 h-20 logo vue" alt="Vue logo" />
    </div>

    <HelloWorld msg="dydx" />
  </div>
</template>


<style>
@font-face {
  font-family: "LM Roman";
  src: local("LM Roman"), url("./assets/fonts/KaTeX_Main-Regular.woff2") format("woff2");
}
</style>