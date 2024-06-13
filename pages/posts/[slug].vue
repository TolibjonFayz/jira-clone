<script setup lang="ts">
const route = useRoute();
</script>

<template>
  <div>Documentation id: {{ route.params.slug }}</div>
</template>

<style lang="scss" scoped></style>
