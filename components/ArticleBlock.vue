<script setup lang="ts">
defineProps<{
  title: string,
  color: string,
  src: string,
}>()
</script>

<template>
  <article
    :style="{ '--color': $props.color }"
    class="
      border-t-4 bg-white row-span-2 h-60 rounded-lg relative p-8
      before:(c_ bg-[var(--color)] absolute top-0 left-0 w-full h-2 rounded-t-lg)
    "
  >
    <header class="text-xl font-semibold mb-4">{{$props.title}}</header>
    <p class="text-gray-600"><slot /></p>
    <img :src="$props.src" alt="" class="absolute bottom-8 right-8">
  </article>
</template>

<style scoped>

</style>
