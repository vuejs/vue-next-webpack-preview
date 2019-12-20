<template>
  <img src="./logo.png">
  <h1>{{ msg }}</h1>
</template>

<script>
export default {
  data() {
    return {
      msg: 'Hello Vue 3!'
    }
  }
}
</script>

<style scoped>
img {
  width: 200px;
}
h1 {
  font-family: Arial, Helvetica, sans-serif;
}
</style>
