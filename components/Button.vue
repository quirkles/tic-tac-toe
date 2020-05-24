<template>
  <button class="button" @click="$emit('click', $event)">
    {{ buttonText }}
  </button>
</template>
<script>
export default {
  props: ['buttonText']
}
</script>
