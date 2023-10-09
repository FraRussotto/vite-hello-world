<script>
  import Title from './components/Title.vue';
  export default {
    name: 'App',
    components: {
      Title
    },
    data(){
      return{
        titolo: "La mia prima App con Vite",
      }
    }
  }

</script>

<template>
  <Title></Title>
  <h1></h1>
</template>


<style>

</style>