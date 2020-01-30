<template>
  <div>
    <div class="row">
      <div class="col-12">
        <div>
          <b-jumbotron header="Home Page" lead="Nuxt JS Application">
            <p>Visit other routes and check the pages</p>
            <nuxt-link class="btn btn-primary" to="/about">About Us</nuxt-link>
            <nuxt-link class="btn btn-primary" to="/blog">Read Blog </nuxt-link>
          </b-jumbotron>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-4">
        <img src="https://i.picsum.photos/id/288/500/500.jpg" alt="" class="img-fluid">
      </div>
      <div class="col-4">
        <img src="https://i.picsum.photos/id/699/500/500.jpg" alt="" class="img-fluid">
      </div>
      <div class="col-4">
        <img src="https://i.picsum.photos/id/639/500/500.jpg" alt="" class="img-fluid">
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>

</style>
