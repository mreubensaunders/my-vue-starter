<template>
  <div id="app">    
    <Nav/>
    <div class="container is-spaced">
        <nav class="level">
        <!-- Left side -->
        <div class="level-left">
          
          <div class="level-item">
            <div class="field has-addons">
              <p class="control">
                <input class="input" type="text" placeholder="Find a post">
              </p>
              <p class="control">
                <button class="button">
                  Search
                </button>
              </p>
            </div>
          </div>
        </div>

        <!-- Right side -->
        <div class="level-right">
          <p class="level-item"><strong>All</strong></p>
          <p class="level-item"><a>Trending <i class="fa fa-heart"></i></a></p>          
          <p class="level-item"><a class="button is-success">New</a></p>
        </div>
      </nav>
      
        
    </div>
  </div>
</template>

<script>
import Nav from './components/Nav.vue'

export default {
  name: 'app',
  components: {
    Nav
  }
}
</script>

<style>
  #app {    
    /* font-family: 'Domine', serif; */

  }
</style>

<style lang="sass">
  @charset "utf-8"
  
  // @import url('https://fonts.googleapis.com/css?family=Domine&display=swap')

  //f22a50 <--nice pink
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


