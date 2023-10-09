<script>
  export default {
    name: 'AppTitle',

    data(){
      return{
        titolo: 'La mia prima app con Vite!'
      }
    }
  }
</script>

<template>
  <h1 class="text-center mb-3 rounded">{{ titolo }}</h1>
</template>

<style>
  h1{
    border: 1px solid lightgray;
  }
</style>