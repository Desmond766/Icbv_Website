<template>
  <TopNavigationBar10 />

  <main>
    <slot />
  </main>
  <Footer10 />
</template>

<script lang="ts" setup>
import TopNavigationBar10 from '@/layouts/sections/components/TopNavigationBar10.vue'
import Footer10 from '@/layouts/sections/components/Footer10.vue'
</script>
