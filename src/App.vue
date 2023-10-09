<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  name: 'App',
  components:{
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div class="container mt-3">
    <AppTitle />

    <AppHero />
  </div>
</template>

<style>

</style>