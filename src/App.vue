<template>
  <v-app>
    <v-main>
      <HelloWorld/>
      <ContactUs/>
      <TestComponent/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TestComponent from './components/TestComponent.vue'
// import ContactUs from './components/ContactUs.vue'


export default {
  name: 'App',

  components: {
    HelloWorld,
    TestComponent
    // ContactUs
  },

  data: () => ({
    //
  }),
}
</script>
