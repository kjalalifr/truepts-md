<script setup lang="ts">
import { useRoute } from 'vue-router';

const route = useRoute()

</script>

<template>
  <h1>Client {{ route.params?.id }} View</h1>
</template>
