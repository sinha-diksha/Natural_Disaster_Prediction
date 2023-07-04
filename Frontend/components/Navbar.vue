<script setup>
const route = useRoute();

let options = ref([])

options.value = [];
</script>

<template>
  <div class="font-mono text-9xl">
    <div class="navbar bg-primary text-primary-content sticky rounded-md z-20">
      <div class="navbar-start">
        <div class="dropdown">
          <label tabindex="0" class="btn btn-ghost lg:hidden">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                 stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M4 6h16M4 12h8m-8 6h16"/>
            </svg>
          </label>
          <ul tabindex="0"
              class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52">
            <li v-for="option in options">
              <NuxtLink :to=option.toLowerCase() class="prose-2xl btn-primary mt-1"
                        :class="route.name === option.toLowerCase() ? 'bg-primary-focus' : ''">
                <h5>{{ option }}</h5>
              </NuxtLink>
            </li>
          </ul>
        </div>
        <NuxtLink class="btn btn-primary prose-2xl"><p class="font-mono text-2xl">Natural Disaster Prediction</p></NuxtLink>
      </div>
      <div class="navbar-end hidden lg:flex">
        <ul class="menu menu-horizontal px-1">
          <li v-for="option in options" class="m-0.5">
            <NuxtLink :to=option.toLowerCase() class="prose-2xl btn-primary"
                      :class="route.name === option.toLowerCase() ? 'bg-primary-focus' : ''">
              <h5>{{ option }}</h5>
            </NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>