<script setup>
import { ref } from 'vue';
import BIT from './BIT.vue';
 
defineProps({
  msg: String,
  test: String,
  
})


</script>

<template>
  
  <div class="bg-red-400">
    <BIT  msg="melat" test="meazii" />
 </div>


</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
