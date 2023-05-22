<template>
  <div class=" max-w-4xl mx-auto">
    <div class="w-full">
      <div class="w-full">
        <div class="space-y-0 text-center">
                            <NuxtLink
          :to="localePath('/')">
          <img src="NOSTRDAM-Dark.png" class="max-h-72 mx-auto block dark:hidden" />

          <img src="NOSTRDAM-Light.png" class="max-h-72 mx-auto hidden dark:block" />
</NuxtLink>

        </div>
      </div>
    </div>
  </div>
</template>
<script setup>

</script>
