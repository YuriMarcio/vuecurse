<template>
  <life-cicle/>
  <primeiroComponente/>
</template>

<script>
  import primeiroComponente from './components/primeiroComponente.vue';
  import lifeCicle from './components/lifeCicle.vue';
  export default{
    name:"app",
    components:{
      primeiroComponente,
      lifeCicle
    }
  }
</script>