<template>
  <div class="container">
    <Button button-text="Create new game" @click="handleClick"></Button>
  </div>
</template>
<script>
import Button from '~/components/Button.vue'

export default {
  components: {
    Button
  },
  methods: {
    handleClick(e) {
      console.log(e) //eslint-disable-line
    }
  }
}
</script>
