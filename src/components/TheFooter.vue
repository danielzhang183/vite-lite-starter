<script setup lang="ts">
function toggleColorMode() {
  return toggleDark()
}
</script>

<template>
  <nav mt-6 inline-flex gap-2 text-xl>
    <button icon-btn @click="toggleColorMode()">
      <div i-carbon-sun dark:i-carbon-moon />
    </button>

    <a
      i-carbon-logo-github icon-btn
      rel="noreferrer"
      href="https://github.com/danielzhang183/vite-lite-starter"
      target="_blank"
      title="GitHub"
    />
  </nav>
</template>
