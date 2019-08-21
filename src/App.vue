<template>
  <div id="app">
    <LibComponentOne />
  </div>
</template>

<script>
import { LibComponentOne } from 'vue-library-sample'

export default {
  name: 'app',
  components: {
    LibComponentOne
  }
}
</script>
