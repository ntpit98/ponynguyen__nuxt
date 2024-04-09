<script setup>
    import AppHeader from "./header.vue"
    import AppFooter from "./footer.vue"

    const colorMode = useColorMode()
    colorMode.preference = 'dark'
</script>

<template>
  <div>
    <AppHeader />
    <slot />
    <AppFooter />
  </div>
</template>