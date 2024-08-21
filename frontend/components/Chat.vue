<template>
  <div class="h-52 w-72 relative bg-neutral-50 border rounded-lg hover:border-sky-200 hover:drop-shadow-md">
    <font-awesome :icon="['fas', 'comment-dots']" class="text-sky-400 size-12 absolute top-4 left-4" />
    <div class="bg-white rounded-lg absolute bottom-0 w-full px-4 py-1">
      <h2 class="font-bold text-lg text-neutral-900">{{ title }}</h2>
      <h3 class="font-semibold text-neutral-500">{{ description }}</h3>          
    </div>
  </div>
</template>

<script setup>
  const props = defineProps({
    title: String,
    description: String
  })
</script>