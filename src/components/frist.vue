<template>
  <div class="hello">
    <button @click="addle">+</button>
    <span>{{this.$store.state.count}}</span>
    <button @click="deep">-</button>
  </div>
</template>

<script>
export default {
  name: 'count',
  methods:{
    addle(){
      this.$store.commit('increment')
      this.fcount++
    },
    deep(){
      this.$store.commit('decrement')
      this.fcount--
    }
  }
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
