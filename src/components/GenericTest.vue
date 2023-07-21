<template>
    <b>{{ value }}</b>
</template>

<script lang="ts" setup generic="T">
defineProps<{
    value: T
}>()
</script>