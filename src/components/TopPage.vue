<template>
  <section class="top-page">
    <HomeHero/>
    <MainPage/>
  </section>
</template>
<script>
import HomeHero from './HomeHero.vue'
import MainPage from './MainPage.vue'

export default {
  components: {
    HomeHero,
    MainPage,
  }
}
</script>
<style lang="scss" scoped>
.top-page {
  padding-bottom: 50px;
}
</style>