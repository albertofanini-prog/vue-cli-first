<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>{{ text }}</h3>
    <h5>{{ dreamText}}</h5>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    text: String,
    dreamText: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
  font-size: 42px;
  margin-bottom: 50px;
}
h3 {
  font-size: 34px;
}
h5 {
  font-size: 28px;
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
