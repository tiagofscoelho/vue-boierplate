<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Hello, World!'
    }
  }
}
</script>

<style lang="scss" scoped>
  h1 {
    color: green;
  }
</style>
