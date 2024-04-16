<script setup lang="ts">
import { useRoute } from 'vue-router';
import {
  computed,
} from 'vue';

const route = useRoute();

const param = computed(() => route.params.paramId);
</script>

<template>
<div>
  Debug

  Param: {{ param }}<br>
  Typeof Param: {{ typeof param }}
</div>
</template>

<style scoped>

</style>
