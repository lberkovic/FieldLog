<script setup>
import { ref } from 'vue'
const greeting = ref('Novo opažanje')
</script>

<template>
  <p class="greeting">{{ greeting }}</p>

<div class="q-pa-md q-gutter-sm">
  <q-btn 
    to="/"
    color="primary" 
    label="Povratak" />
  </div>


</template>

<style>
.greeting {
  color: red;
  font-weight: bold;
}
</style>

