<template>
  <v-app>
    
    <v-main>
      <section>
      <heading/>
      </section>
      <hr/>
      <section>
      <wrapper/>
      </section>
    </v-main>
  </v-app>
</template>

<script>
import heading from './components/header'
import wrapper from './components/main'

export default {
  name: 'App',

  components: {
  
    heading,
    wrapper
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>

</style>
