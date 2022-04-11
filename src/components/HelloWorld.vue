<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  },
})
</script>

<template>
  <button class="button"> {{ msg }} </button>
</template>

<style scoped>
  .button {
    border: 3px solid black;
    background-color: aliceblue;
  }
</style>

