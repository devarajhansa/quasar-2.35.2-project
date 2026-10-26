<template>
  <q-page class="flex flex-center">
    <q-btn color="secondary" to="/" label="Go to Index Page" no-caps />
  </q-page>
</template>

<script setup>
//
import { ref } from 'vue';

const r = ref(0);

console.log('r', r.value);


</script>
