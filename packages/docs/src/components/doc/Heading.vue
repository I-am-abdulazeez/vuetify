<template functional>
  <core-goto class="core-goto--heading">
    <doc-markdown v-bind="$attrs"><slot /></doc-markdown>
  </core-goto>
</template>

<script>
  export default {
    inherritAttrs: false,
  }
</script>

<style lang="sass">
.core-goto--heading
  h1
    font-size: 3rem
    font-weight: 300

  h2
    font-size: 2rem
    font-weight: 500

  h3
    font-size: 1.25rem
    font-weight: 500

  @media only screen and (max-width: 600px)
    h1
      font-size: 2rem
      font-weight: 500

    h2
      font-size: 1.25rem

    h3
      font-size: 1rem
</style>
