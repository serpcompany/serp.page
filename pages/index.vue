<script setup>

useHead({
  link: [{ rel: 'canonical', href: 'https://serp.page' }],
})

useSeoMeta({
  title: 'Are you a Nuxter?',
  ogTitle: 'Are you a Nuxter?',
  description: 'Discover your contributions to unlock the nuxter role on Nuxt Discord server.',
  ogDescription: 'Discover your contributions to unlock the nuxter role on Nuxt Discord server.',
  ogImage: 'https://serp.page.co/social-card.jpg',
  ogImageAlt: 'Nuxters',
  twitterImage: 'https://serp.page.co/social-card.jpg',
  ogUrl: 'https://serp.page.co'
})
</script>

<template>
  <div class="text-green-400 flex flex-col gap-y-[72px] py-10 lg:py-40">
    <HomeHero />
    <HomeContributors />
  </div>
</template>
