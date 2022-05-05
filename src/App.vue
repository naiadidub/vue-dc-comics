<template>
  <div id="app">
    <headerContent/>
    <mainContent/>
    <footerContent/>
  </div>
</template>

<script>
import headerContent from './components/headerContent.vue'
import mainContent from './components/mainContent.vue'
import footerContent from './components/footerContent.vue'

export default {
  name: 'App',
  components: {
    headerContent,
    mainContent,
    footerContent
  }
}
</script>

<style lang="scss">
 


</style>
