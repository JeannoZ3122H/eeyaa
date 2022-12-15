<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <RouterView />
  <!--<RouterView />-->
  <!--<Service/>-->
  <!--<Profile/>-->
  <!--<Statut/>-->
  <!--<Professionnel/>-->
  <!--<Confidentialité/>-->
  <Confidentialité/>
</template>

<script>
// import Service from './views/NotreConcept.vue'
// import Profile from './views/Inscription-Profile.vue'
// import Statut from './views/Inscription-Statut-PhotoProfile.vue'
// import Professionnel from './views/Inscription-StatutPhoto-Professionnel.vue'
// import Confidentialité from './views/Inscription-InfosConfidentitielles.vue'
export default{
  components:{
    // Service,
    // Profile,
    // Statut,
    // Professionnel,
    // Confidentialité,
  }
}
</script>
<style>
@media screen and (max-width: 992px){
  body{
    background-position: top center !important;
  }
}
</style>
