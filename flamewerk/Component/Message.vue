<template>
  <div class=" max-w-4xl mx-auto">
    <div class="w-full">
      <div class="w-full">
        <div class="space-y-0 text-center">

          <h2
            class="text-3xl font-bold tracking-tight sm:text-4xl text-colorTxtLight dark:text-colorTxtDark">
            {{ $t("homepage.title") }} {{ project.$state.name }} !
          </h2>
          <p class="text-2xl text-gray-500 dark:text-pink-400">
            <!-- {{ $t("homepage.subtitle") }} -->
            The First Nostr EU meetup hosted in Amsterdam
          </p>
<p class="text-center pt-6">
                  <NuxtLink
          :to="localePath('/whitepaper')"

          class="text-white bg-gray-700 hover:text-white group  px-6 py-2 text-lg font-medium rounded-md text-center max-w-sm mx-auto "
          >READ CURRENT STATE WHITEPAPER</NuxtLink
        >
</p>

        </div>
      </div>
    </div>
  </div>
</template>
<script setup>
import { useSettings } from "~/flamewerk/project";

const project = useSettings()

</script>
