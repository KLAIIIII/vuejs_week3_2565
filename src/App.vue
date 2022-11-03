<template>
  <div>
    <!-- MENU -->
   <MenuComponent />

   <router-view />

   <!-- Footer -->
   <FooterComponent />

   <!-- Slide -->
   <SlideComponent />

  </div>
</template>

<script>
import MenuComponent from '@/components/MenuComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue'
import SlideComponent from '@/components/SlideComponent.vue'

export default {
  name: 'HomeView',
  components: {
    MenuComponent,
    FooterComponent,
    SlideComponent,
  }
}
</script>