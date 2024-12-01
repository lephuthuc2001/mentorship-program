<script setup lang="ts">
import { useDateFormat, useNow } from '@vueuse/core'

const formatted = useDateFormat(useNow(), 'dddd YYYY-MM-DD HH:mm:ss')
</script>

<template>
  <div>{{ formatted }}</div>
</template>
