<script setup lang="ts">
import Footer from '~/components/app/Footer.vue'
import Header from '~/components/app/Header.vue'
</script>

<template>
  <div class="p-4 min-h-dvh flex flex-col gap-4">
    <Header />
    <div class="grow">
      <slot />
    </div>

    <Footer />
  </div>
</template>
