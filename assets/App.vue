<template>
  <h1 class="block__element--modifier">{{ world }}</h1>
</template>

<script>
  export default {
    data() {
      return {
        world: 'Hello!'
      }
    }
  }
</script>

<style lang="scss">
  .block {
    &__element {
      &--modifier {
        color: green;
      }
    }
  }
</style>
