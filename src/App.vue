<script setup>
  import HelloWorld from './components/HelloWorld.vue';
  // import {useQuery} from '@vue/apollo-composable'
  import countreis from './components/Towna.vue'

</script>

<template>
  
  
<div class="bg-red-400">
  <HelloWorld :mim=A0 msg="melat" test="lovely" />
</div>


  <countreis />


  {{ test }}
  {{ msg }}
  {{ mim }}
</template>

<style  scoped >
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
     
</style>
