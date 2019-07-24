<template>
  <div>
    <h3>Hello world! This is Dashboard! <strong>Nuxt.js + Laravel</strong></h3>
  </div>
</template>

<script>
  export default {
    middleware: ['auth'],
    data() {
      return {
        form: {
          title: '',
          body: ''
        }
      }
    },
    methods: {
      //
    }
  }
</script>
