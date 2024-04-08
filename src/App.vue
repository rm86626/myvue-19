<template>
  <div>
     <h3>App组件</h3>
     <p>{{ count }}</p>
     <button @click="add">+</button>
  </div>
</template>

<script setup lang="ts">
import {ref} from 'vue'
let count=ref(0);
let add=()=>{
  count.value++;
}
</script>

<style scoped>

</style>