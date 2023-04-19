Counter
<template>
   <div>
      <button @click="decrement()">-</button>
      {{  counter }}
      <button @click="increment()">+</button>
   </div>
</template>

<script setup>
import { useCounter } from './composables/useCounter'

const { counter, decrement, increment} = useCounter()

</script>

