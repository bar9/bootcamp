<template>
  <div>
    <ul v-for="mountain in mountains" :key="mountain.id">
          <li>{{ mountain.title }} ({{ mountain.height }})</li>
    </ul>
  </div>
</template>
<script setup>
const { data: mountains } = await useFetch('https://api.nuxtjs.dev/mountains')
</script>