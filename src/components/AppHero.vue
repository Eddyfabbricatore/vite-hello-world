<script>
  export default {
    name: 'AppHero',
    data(){
      return{
        imgSrc: 'jumbo.png'
      }
    },
    methods:{
      getImgSrc(img){
        return new URL(`../assets/img/${img}`, import.meta.url).href;
      }
    }
  }
</script>

<template>
  <div id="jumbotron">
    <img :src="getImgSrc(imgSrc)" alt="Jumbotron">
  </div>
</template>

<style scoped>
  img{
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
</style>