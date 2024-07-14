<template>
  <div>{{ $route.params.id }}</div>
  <mylist :message="parentMessage" />
</template>

<script lang="ts" setup>
const param = useRoute();
console.log(22, param.params.id);
const parentMessage = ref("Hello from Parent");
</script>

<style></style>
