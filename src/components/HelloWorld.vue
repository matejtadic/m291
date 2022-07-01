
<template>
<head>
  <link rel="Javascript" href="main.js">
</head>
<section>
    <div class="container">
      <form >
        <input type="number" placeholder="Enter a number">
        <button type="submit">Submit</button>
      </form>
      <div class="number-fact">Give a number and i will tell you a interesting fact.</div>
    </div>
  </section>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
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
