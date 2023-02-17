<script setup>
const {cars} = useCars;
const props = defineProps({
  description: String,
})
</script>

<template>
  <div class="mt-5">
    <p class="mb-10">
      {{ description }}
    </p>
  </div>
</template>