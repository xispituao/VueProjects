<template>
  <div class="hello">
    <h1 :title="msg">{{msg}}</h1>
  </div>
</template>

<style>

</style>

<script>
  export default {
    data (){
      return{
        msg: 'Bem-Vindo a sua primeira app com Vue.js'
      }
    }
  }
</script>
