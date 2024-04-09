<script>
import { ref } from "vue";
</script>

<template>
  <header class="bg-white dark:bg-gray-900">
    <nav
      class="fixed inset-x-0 top-0 z-10 mx-auto p-6 flex items-center justify-between bg-gradient-to-r from-blue-600 via-blue-800 to-blue-900 shadow-lg dark:from-gray-700 dark:via-gray-800 dark:to-gray-900"
    >
      <div class="flex items-center justify-between">
        <div>
          <a
            role="button"
            class="text-2xl font-bold text-white hover:text-gray-300 lg:text-3xl"
            href="/"
          >
            Brand
          </a>
        </div>
      </div>

      <div class="flex items-center justify-between">
        <div>
          <a
            role="button"
            class="text-md font-bold text-white hover:text-gray-300"
            href="/contact"
          >
            Contact
          </a>
        </div>
      </div>
    </nav>
  </header>
</template>

<style lang="postcss">
body {
  @apply min-h-screen bg-white dark:bg-gray-800 dark:text-gray-200;
}
</style>
