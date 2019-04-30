<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="starter-template">
      <div class="mt-2">
        <p class="lead">Made with vue.js and bootstrap.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'top',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
</style>
