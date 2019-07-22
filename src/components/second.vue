<template>
  <div class="hello">
    <input type="text" id="owen" v-model.number="number">
        <count></count>
  <div>{{this.$store.state.count }}</div>
  </div>
</template>

<script>
import count from './frist.vue'
export default {
  name: 'createInput',
  components:{count},
  data(){
    return{
      number:0
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
