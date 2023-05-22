<template>
  <div class="overflow-hidden bg-white shadow sm:rounded-lg max-w-4xl mx-auto mb-12">

    <div class="border-t border-gray-200 px-4 py-5 sm:px-6">
      <dl class="grid grid-cols-1 gap-x-4 gap-y-8 sm:grid-cols-2">

        <slot />
        



      </dl>
    </div>
  </div>










</template>

<script setup>
const page = defineProps({
  image: {
    type: String,
    default: '/stock/Flamewerk-DarkLogo.png'
  }
})


</script>
