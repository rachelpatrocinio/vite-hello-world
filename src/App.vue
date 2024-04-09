<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default { 
  components: {
    AppTitle,
    AppHero
  }
}

</script>

<template>
  <div id="app">
    <AppHero />
    <AppTitle />
  </div>
</template>

<style>
#app{
  height: 100vh;
}
</style>