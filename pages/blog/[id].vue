<script setup lang="ts">
const route = useRoute();
</script>

<template>
  <h1>Blog Artikel mit der ID: {{ route.params.id }}</h1>
</template>
