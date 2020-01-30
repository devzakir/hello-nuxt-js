<template>
  <div>
    <navbar></navbar>
    <section class="body mt-3">
      <div class="container">
          <nuxt />
      </div>
    </section>

  </div>
</template>

<script>
import navbar from '~/components/Navbar.vue';

export default {
    components: {
      navbar,
    }
}
</script>
<style>

</style>