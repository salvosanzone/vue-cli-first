<template>
  <div class="container">
    <Header/>
    
  </div>
</template>

<script>
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
 .container{
   width: 600px;
   margin: 10px auto;
   padding: 50px;
   background-color: brown;
   box-shadow: 10px 20px 25px rgba(0, 0, 0, .3);
   text-align:center ;
 }
</style>
