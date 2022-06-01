<template>
  <div class="hello">
    <h1>working</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },

  mounted: function () {
    console.log("shaun")
    this.test()
  },
  methods: {
    test(){
      console.log("shaun hossain") 
    }
  }
  
}



</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
