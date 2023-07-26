<template>
  <div>
   <Header/>
  <Products/>   
  </div>
  
</template>

<script setup>
//import { onMounted,ref } from 'vue';
//import api from "@/api.js";
import {ref} from 'vue';
import Header from './components/Layout/Header.vue';
import Products from './components/Product2Column.vue';


</script>




<style lang="scss">
*{
  box-sizing: border-box;
}
.body{
  margin: 0;
  padding: 0;
}
.container{
  max-width: 1440px;
  margin: auto;
}
</style>
