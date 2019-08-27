<template>
  <v-app class="grey lighten-4"> 
    <Navbar /> 
      <!-- All page contents should be inside v-content. The navbar might be above and
      footer below -->
    <v-content class="mx-4 mb-4">
      <router-view></router-view>
    </v-content>

  </v-app>
</template>

<script>
import Navbar from '@/components/Navbar'

export default {
  name: 'App',
  components: {Navbar},
  data: () => ({
    //
  }),
};
</script>
