<template>
  <v-app>

    <v-navigation-drawer/>

    <v-app-bar/>

    <v-carousel/>

    <Footer/>
    
  </v-app>
</template>

<script>
import Footer from '@/components/templates/Rodape.vue'
import Menu from '@/components/templates/Menu.vue'
import NavBar from '@/components/templates/NavBar.vue'
import Carousel from '@/components/widgets/Carousel.vue'

export default {
  components: {
    Footer,
    vNavigationDrawer: Menu,
    'v-app-bar': NavBar,
    vCarousel: Carousel,
    }
}
</script>
