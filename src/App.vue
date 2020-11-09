<template lang="pug">
#app
  Top
  #content
    #left
      Menu
      update
    #right
      mar
      Main
  Footer
</template>

<script>
import Top from './components/Top.vue'
import Menu from './components/Menu.vue'
import update from './components/update.vue'
import mar from './components/mar.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Top,
    Menu,
    update,
    mar,
    Main,
    Footer
  }
}
</script>
