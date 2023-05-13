<template>
  <div>
    Hello World, SSR!
  </div>
  <h2 @click="addCount">
    {{ count }}
  </h2>
</template>

<script lang="ts" setup>
import { ref } from 'vue';

const count = ref(0);

const addCount = () => {
  count.value++;
};
</script>
