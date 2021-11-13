<template>
  <div>
    <header class="header" >Aboout Layout</header>
    <AppLayoutLinks />
    <slot />
  </div>
</template>

<script>
import AppLayoutLinks from '@/layouts/AppLayoutLinks'
export default {
  name: "AppLayoutAbout",
  components: {AppLayoutLinks}
}
</script>

<style scoped>
.header {
  height: 5rem;
  background-color: blue;
}
</style>