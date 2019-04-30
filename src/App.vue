<template>
  <div id="app">
    <HeaderItem/>
    <div class="text-center">
      <router-view/>
    </div>
  </div>
</template>

<script>
  import HeaderItem from './components/HeaderItem'

  export default {
    components : {
      HeaderItem
    }
  }
</script>
