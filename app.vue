<script setup>
useHead({
  htmlAttrs: {
    lang: "fr",
  },
  charset: "utf-8",
  title: "Benin Tech Communities",
  meta: [
    {
      name: "description",
      content: "Découvrez les communautés Tech faconnant l'écosystème au Bénin ",
    }
  ],
  link: [
    {
      rel: "icon",
      type: "image/svg",
      href: "/community.svg",
    },
  ],
});
</script>
<template>
  <div>
    <Navbar />
    <NuxtPage />
  </div>
</template>
