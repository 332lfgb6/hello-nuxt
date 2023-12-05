<template>
  <div>{{greet}}</div>
  <button @click="click">change</button>
</template>

<script lang="ts" setup>
const greet=ref('hi')

const click = () => {
  greet.value='hello'
}
</script>

<style lang="scss" scoped></style>
