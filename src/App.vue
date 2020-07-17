<template>
  <div>
    <myname v-for="i in 3"></myname>
  </div>  
</template>

<script>
import Homy from './assets/Components/Home'
export default {
  components:{
    myname : Homy
  }
}
</script>

<style>
</style>
