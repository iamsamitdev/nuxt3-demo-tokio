<script lang="ts" setup>
  const route = useRoute()
  console.log(route)
  const slug = ref(route.params.slug)
</script>

<template>
  <div>
    <h1>Backend Page</h1>
    <p v-if="$route.params.slug">
      Backend: {{ $route.params.slug }}
    </p>
    <ul>
      <li v-for="item in slug" :key="item">{{ item }}</li>
    </ul>
  </div>
</template>

<style scoped></style>
