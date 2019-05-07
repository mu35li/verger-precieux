<template lang="pug">
  b-container(fluid).d-flex.justify-content-center.align-items-center.flex-column.vh-100
    Navbar.mb-auto
    b-row.justify-content-center.align-items-center.flex-column.mb-auto
      b-col.text-center
        Logo.img-fluid.w-50
      b-col
        p.h1.text-white.text-center
          strong #ComingSoon
    
</template>

<script>
import Logo from '~/components/Logo.vue'
import Navbar from '../components/Navbar'

export default {
  components: {
    Logo,
    Navbar
  }
}
</script>

<style lang="scss">
  body {
    background: #16161D;
  }
  .vh-50 {
    height: 50vh;
  }
  
</style>
