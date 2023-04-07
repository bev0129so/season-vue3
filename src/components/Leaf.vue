<template>
 <div>This is a child component {{ childProps }}</div>
</template>

<script setup>
    import { defineProps } from 'vue'
    defineProps({
        childProps: {
            type: String,
            default: 'a'
        }
    })
</script>
<style lang="scss" scoped>
</style>
