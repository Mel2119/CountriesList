<script setup>
import {inject} from 'vue'
defineProps({
  msg: String,
  test: String,
})
let message = inject('name');
</script>
<template>
    <h1>{{ message }}</h1>
    
</template>
<style>

</style>