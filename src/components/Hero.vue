<template>
  <div class="hello">
    <h1>{{ titlejumbo }}</h1>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line
  name: 'jumbotron',
  data(){
    return {
      titlejumbo: 'Questo è un jumbotron'
    }
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
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
