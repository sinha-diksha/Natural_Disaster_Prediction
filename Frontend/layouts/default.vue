<template>

  <div class="p-4 min-h-screen flex flex-col">
    <Navbar/>
    <slot/>
  </div>

</template>

<script setup>


const router = useRouter()
const route = useRoute()

</script>


<style scoped>

</style>