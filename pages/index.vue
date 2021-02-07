<template>
  <div>Test</div>
</template>

<script>
import { useFetch, ref } from '@nuxtjs/composition-api'

export default {
  setup () {
    useFetch(() => {})
  }
}
</script>
