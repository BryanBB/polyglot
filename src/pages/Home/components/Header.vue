<script setup lang="ts">
</script>

<template>
  <header class="bg-#fff dark:bg-#1f262a">
    <h3 center-y text-2xl>
      <div w-10 m-1 mt-2>
        <!-- 🤖️ -->
        <img w-full src="/favicon.ico" alt="">
      </div>
      <span select-none class="text-gradient ">Polyglot</span>
    </h3>
  </header>
</template>

<style scoped>
 .text-gradient {
    background-image: var(--accent-gradient);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
</style>
