<template>

   <ul>
     <li>糖糖</li>
     <li>丫丫</li>
     <li>糖宝</li>
     <li>{{msg}}</li>
   </ul>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul {
  list-style-type: none;
  padding: 0;
}
</style>
