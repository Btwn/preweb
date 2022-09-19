<template>
  <v-app>
    <v-main>
      <Cliente/>
    </v-main>
  </v-app>
</template>

<script>
import Cliente from './components/Cliente.vue'

export default {
  name: 'App',

  components: {
    Cliente,
  },

  data: () => ({
    //
  }),
}
</script>
