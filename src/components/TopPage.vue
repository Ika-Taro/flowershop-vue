<template>
  <section class="top-page">
    <HomeHero/>
    <AppHeader/>
    <ShopInfo/>
  </section>
</template>
<script>
import HomeHero from './HomeHero.vue'
import AppHeader from './AppHeader.vue'
import ShopInfo from './ShopInfo.vue'

export default {
  components: {
    HomeHero,
    AppHeader,
    ShopInfo,
  }
}
</script>
<style lang="scss" scoped>
.top-page {
  padding-bottom: 50px;
}
</style>