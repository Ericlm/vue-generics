<script setup lang="ts">
import GenericTest from './GenericTest.vue';

defineProps<{
  msg: string
}>()
</script>

<template>
  <GenericTest value="Hello World!" random="coucou" />
</template>
