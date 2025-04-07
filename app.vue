<template>
  <NuxtPage />
</template>

<script setup lang="ts">
useHead({
  title: "Browser",
  link: [{ rel: "icon", type: "image/x-icon", href: "/favicon.ico" }],
  meta: [
    { charset: "utf-8" },
    { name: "viewport", content: "width=device-width, initial-scale=1" },
    { key: "theme-color", name: "theme-color", content: "#fff" },
  ],
  htmlAttrs: {
    lang: "en",
  },
});
</script>
