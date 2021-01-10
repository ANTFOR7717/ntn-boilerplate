<template>
  <div class="main text-center flex flex-col items-center justify-center">
    <!-- <logo /> -->
    <h1 class="title">Droofin - Drinks Delivered</h1>
    <h2 class="subtitle">by <a href='https://afresolutions.com'>AF Resolutions</a></h2>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'

export default {
  // components: {
  //   Logo
  // },
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }]
    }
  }
}
</script>
