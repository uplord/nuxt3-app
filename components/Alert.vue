<script setup>
const props = defineProps({
  type: {
    type: String,
    default: 'info'
  },
  message: {
    type: String,
  }
})
</script>

<template>
  <div class="alert" :class="type">{{ message }}</div>
</template>