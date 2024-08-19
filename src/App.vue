<template>
  <div>
    <CarrosAntigos />
    <RollsRoyce />
    <FordComp />
    <ChevroLet />
  </div>
</template>

<script>
import CarrosAntigos from './components/CarrosAntigos.vue';
import RollsRoyce from './components/RollsRoyce.vue';
import FordComp from './components/FordComp.vue';
import ChevroLet from './components/ChevroLet.vue';


export default {
  name: 'App',
  components: {
    CarrosAntigos,
    RollsRoyce, 
    FordComp,
    ChevroLet
  }
}
</script>

<style src="./assets/style.css"></style>
