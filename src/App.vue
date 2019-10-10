<template>
  <div id="app">    
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
  /* #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif
    -webkit-font-smoothing: antialiased
    -moz-osx-font-smoothing: grayscale
    text-align: center
    color: #2c3e50
    margin-top: 60px
  } */
</style>

<style lang="sass">
  @charset "utf-8"

  // COLORS
  $primary: #00d1b2
  $info: #209CEE
  $success: #23D160
  $warning: #FFDD57
  $danger: #FF3860
  $light: #F5F5F5
  $dark: #363636

  // TEXT
  $text: #4A4A4A
  $link: #3273DC
  $title-family: false
  $button-family: false

  // BREAKPOINTS
  $gap: 32px
  $tablet: 769px
  $desktop: 960px + (2 * $gap)
  $widescreen: 1152px + (2 * $gap)
  $fullhd: 1344px + (2 * $gap)
  $widescreen-enabled: true
  $fullhd-enabled: false

  // LAYOUT
  $section-padding: 3rem 1.5rem
  $section-padding-medium: 6rem 1.5rem
  $section-padding-large: 9rem 1.5rem

  @import "~bulma/bulma.sass"
</style>


