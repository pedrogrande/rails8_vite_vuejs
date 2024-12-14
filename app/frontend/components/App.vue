<template>
  <div>
    <h1>{{ msg }}</h1>
  </div>
</template>

<script setup>
defineProps({
  msg: String
})
</script>

<style lang="scss" scoped>
h1 {
  color: red;
}
</style>
