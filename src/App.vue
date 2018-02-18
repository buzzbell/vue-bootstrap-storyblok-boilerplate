<template lang="pug">
  <div id="app">
    header
      nav.navbar.navbar-expand-md.navbar-light.bg-light
        a.navbar-brand
          img.d-inline-block(src="./assets/logo.png", style="height:50px")
          |Poverty's Pets
        button.navbar-toggler.collapsed(type="button", data-toggle="collapse", data-target="#navbarCollapse", aria-controls="navbarCollapse", aria-expanded="false", aria-label="Toggle Navigation")
          span.navbar-toggler-icon
        .collapse.navbar-collapse#navbarSupportedContent
          ul.navbar-nav.ml-auto
            li.nav-item.active
              a(class="nav-link", href="#") Home
                span.sr-only Current
            li.nav-item 
              a.nav-link(href="#") About Us
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">
#app {
  // font-family: 'Avenir', Helvetica, Arial, sans-serif;
  // -webkit-font-smoothing: antialiased;
  // -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  // color: #2c3e50;
  // margin-top: 60px;
}
</style>
