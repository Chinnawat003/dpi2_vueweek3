<template>
  <div>
    
    <MenuComponent />
    <FooterComponent />
    <ProfileView />

  </div>
</template>

<script>
// @ is an alias to /src
import MenuComponent from '@/components/MenuComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue'
import ProfileView from '@/views/ProfileView.vue'
export default {
  name: 'HomeView',
  components: {
    MenuComponent,
    FooterComponent,
    ProfileView,
  }
}
</script>
