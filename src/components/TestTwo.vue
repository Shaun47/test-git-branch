<template>
  <div >
    <h1>working test 2 {{title}} {{summation}}</h1>
    <p>random message starts</p>
    <button>close</button>
  </div>
</template>

<script>
export default {
  name: 'TestTwo',
  props:{
    title:String,
    summation: Number,

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
