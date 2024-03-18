<script setup>
useSeoMeta({
  ogTitle: "Home",
  ogDescription: "Anime Mallu - A streaming service for weebo...",
  ogUrl: useRoute().fullPath,
  twitterTitle: "Home",
  twitterDescription: "Anime Mallu - A streaming service for weebo...",
  twitterCard: "summary",
});

useHead({
  htmlAttrs: {
    lang: "en",
  },
  title: "Home",
});
</script>

<template>
  <PgCompsLandingPage />
</template> 

<style></style>
