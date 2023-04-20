<template>
  <Navbar />
  <Aboutme />
  <Work />
  <Footer />
</template>

<script>
import Navbar from "@/components/Navbar.vue"
import Aboutme from "@/components/Aboutme.vue"
import Work from "@/components/Work.vue"
import Footer from "@/components/Footer.vue"
export default {
  name: 'App',
  components: {
    Navbar,
    Aboutme,
    Work,
    Footer,
  },
  
};
</script>

<style>

</style>
