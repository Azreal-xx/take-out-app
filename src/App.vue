<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <footer-guide v-show="$route.meta.showFooter"/>
    <router-view/>
  </div>
</template>

<script>
import FooterGuide from './components/FooterGuide.vue';
export default {
  name: 'App',
  components: {
    FooterGuide
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">
    .app
     width 100%
     height 100%
     background #f5f5f5
</style>
