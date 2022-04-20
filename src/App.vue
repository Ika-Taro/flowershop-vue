<template>
  <v-app>
    <v-main>
      <HelloWorld/>
      <AppFooter/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',

  components: {
    HelloWorld,
    AppFooter
  },

  data: () => ({
    //
  }),
}
</script>
