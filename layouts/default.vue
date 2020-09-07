<template>
  <v-app>
    <v-app-bar fixed color="transparent" flat>
      <zk-navbar></zk-navbar>
    </v-app-bar>
      <v-main light>
        <nuxt />
      </v-main>

      <v-footer app color="transparent">
        <zk-footer />
      </v-footer>
      
  </v-app>
</template>

<script>
import zkFooterVue from '~/components/global/zk-footer.vue'
import zkNavbarVue from '~/components/global/zk-navbar.vue'


export default {
  
}
</script>

<style>
.fullscreen {
  background-size: cover;
  width: 100vmax;
  height: 100vh;
  
}



</style>