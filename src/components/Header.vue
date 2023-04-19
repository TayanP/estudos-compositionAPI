<template>
  {{  counter  }}
</template>

<script>
import { useCouter } from '../components/composables/useCounter'

const { counter } = useCouter()

</script>