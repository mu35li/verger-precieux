<template lang="pug">
  b-container(fluid)
    b-navbar(toggleable='lg', type='dark').nav-transparent
      b-navbar-brand(href='#') Verger Précieux
      b-navbar-toggle(target='nav-collapse')
      b-collapse#nav-collapse(is-nav='')
        // Right aligned nav items
        b-navbar-nav.ml-auto
          b-nav-item(href='#') Home
</template>

<script>
  export default {
    name: "Navbar"
  }
</script>

<style scoped lang="scss">
  .nav-transparent {
    background: transparent !important;
  }
</style>
