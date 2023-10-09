<script>
export default {
  name: 'Title',
  data(){
    return  {
      text: 'La mia prima App con Vite!',
    }
  }
}
</script>

<template>
  <h1>{{ text }}</h1>
</template>


<style scoped>
  h1{
    text-align: center;
    margin-top: 30px;
    font-size: 3rem; 
  }
</style>