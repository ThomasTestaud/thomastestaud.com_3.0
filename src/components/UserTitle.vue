<template>
  <div class="hello">
    <h1>{{ userName }}</h1>
    <p>{{ userTitle }}</p>
  </div>
</template>

<script>
export default {
  name: 'UserTitle',
  props: {
    userName: String,
    userTitle: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
