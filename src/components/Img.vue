<template>
  <div>
    <img 
      :src="src" 
      :alt="alt"
      class="rounded-md shadow-lg"
    >
  </div>
</template>

<script setup>
defineProps({
  src: {
    type: String,
    default: ''
  },
  alt: {
    type: String,
    default: ''
  }
})
</script>