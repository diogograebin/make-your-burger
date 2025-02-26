<template>
  <Navbar />
  <router-view/>
</template>

<script>

import Navbar from "./components/Navbar.vue";

export default{
  components:{
    Navbar
  },

  data(){
    return{

    }
  }
}


</script>

<style>

</style>
