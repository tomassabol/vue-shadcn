<script setup lang="ts">
import Button from "./components/Button.vue";
import DropDownMenu from "./components/DropDownMenu.vue";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div
    class="w-screen h-screen gap-2 items-center justify-center flex flex-col"
  >
    <div class="flex gap-2">
      <a href="https://vitejs.dev" target="_blank">
        <img src="/vite.svg" class="logo" alt="Vite logo" />
      </a>
      <a href="https://vuejs.org/" target="_blank">
        <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
      </a>
    </div>
    <HelloWorld msg="Vite + Vue" />
    <Button @click.prevent="console.log('shadcn')" />
    <DropDownMenu />
  </div>
</template>
