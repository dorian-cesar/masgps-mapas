<template>

<div class="container">
  <div class="card my-3">
  <div class="card-body">
    <h3>Mi BUS</h3>
   
  </div>
</div>
  <MapBus></MapBus>
  <br>
  
  <Selector></Selector>
</div>
  

   
</template>

<script>

import MapBus from './components/MapBus.vue';
import Selector from './components/Selector.vue';



export default {
  components: {MapBus, Selector},
  
  


}
</script>

<style>


</style>