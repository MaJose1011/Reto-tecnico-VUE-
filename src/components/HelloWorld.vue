<template>
    <TiendaReto />
</template>

<!--This Vue component script imports another component named TiendaReto, defines its own name and props, and registers TiendaReto as a child component:-->
<script>

import TiendaReto from './TiendaReto.vue'

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components:{
    TiendaReto
  },
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
