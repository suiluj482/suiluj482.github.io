<script lang="ts" setup>

const githubUrl = 'https://github.com/suiluj482'

</script>

<template>
  <div class="min-h-screen bg-white dark:bg-gray-900 flex flex-col items-center pt-20">
    <UCard class="p-8 text-center w-full max-w-md shadow-lg">
      <NuxtPicture
        format="webp,avif"
        src="/images/js.png"
        alt="Logo"
        class="mx-auto mb-4 w-20 h-20 rounded-full shadow-md"
      />  
      <h1 class="text-3xl font-bold text-gray-800 dark:text-white">
        Julius Schuchert
      </h1>

      <div class="mt-4">
        <NuxtLink
          :href="githubUrl"
        >
          <UIcon 
            :to="githubUrl"
            name="i-lucide:github"
            class="size-7"
          />
        </NuxtLink>
      </div>
    </UCard>
  </div>
</template>
