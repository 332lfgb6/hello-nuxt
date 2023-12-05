<template>
  <div>{{greet}}</div>
  <div>{{greet}}</div>
  <div>{{greet}}</div>
  <div>{{greet}}</div>
  <div>{{greet}}</div>
  <div>{{greet}}</div>
  <button @click="click">change</button>
</template>

<script lang="ts" setup>
const greet=ref('cc')

const click = () => {
  greet.value='hell'
}
</script>

<style lang="scss" scoped></style>
