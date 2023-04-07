<template>
  <div>This is parent</div>
  <leaf :childProps="myprops" />
</template>

<script setup>
import Leaf from './Leaf.vue'
import { ref } from 'vue'
const myprops = ref('2')
</script>
<style lang="scss" scoped></style>
