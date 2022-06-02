<template>
  <div >
    <!-- <h1>working test</h1> -->
    <TestTwo title="checking props" summation="50"></TestTwo> 

    <button @click="showpopup = true">Show Pop up</button>
  </div>
</template>

<script>
import TestTwo from './TestTwo.vue'


export default {
  name: 'TestTem',
  components: {
    TestTwo,
},
data(){
  return{
    showpopup : false
  }
},
  mounted: function () {

  },
  methods: {

  }
  
}



</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
