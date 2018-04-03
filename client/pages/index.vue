<template>
  <h1 class="red">Hello {{ name }}!</h1>
</template>

<script>
export default {
  data () {
    return { name: 'World' }
  }
}
</script>

<style lang="scss">
  $color: green;
  .red {
    color: $color;
  }
</style>
