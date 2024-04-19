<template>
  <div>
    {{ counter.count }}
    <button class="click" @click="counter.increment()">Click</button>
  </div>
</template>

<script setup>
const counter = useCounterStore()
</script>