<script lang="ts" setup></script>

<template>
  <div>
    <h1>Category Page</h1>
      <p v-if="$route.params.slug">Category: {{ $route.params.slug }}</p>
  </div>
</template>

<style scoped></style>
