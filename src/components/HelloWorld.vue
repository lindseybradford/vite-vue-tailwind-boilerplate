<template>
  <h1 class="font-sans text-4xl font-bold">{{ msg }}</h1>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String,
})

const state = reactive({ count: 0 })
</script>
