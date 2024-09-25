<template>
  <q-page class="flex flex-center">
    <h1>{{ message }}</h1>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage',
  data() {
    return {
      message: 'Hola Mundo!'
    }
  }
})
</script>