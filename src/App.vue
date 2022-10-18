<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <nav class="bg-purple-600 text-white">
      <div class="container mx-auto">
        <div class="flex items-center">
          <RouterLink
            to="/"
            class="
              inline-block
              px-16
              py-4
              transition-colors
              hover:bg-purple-500
              duration-300
            "
            >Home</RouterLink
          >
          <RouterLink
            to="/todos"
            class="
              inline-block
              px-16
              py-4
              transition-colors
              hover:bg-purple-500
              duration-300
            "
            >Todos</RouterLink
          >
        </div>
      </div>
    </nav>
  </header>

  <RouterView />
</template>

<style scoped>
</style>
