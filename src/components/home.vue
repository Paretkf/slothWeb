<template>
  <section class="hero is-success is-fullheight slothBody">
    <div class="hero-body">
      <div class="container">
        <div class="columns is-centered">
          <img src="../assets/logo.png" width="40%" height="80%">
        </div>
        <div class="columns is-centered">
          <div class="title is-1">
            Create your own website
          </div>
        </div>
      </div>
    </div>
  </section>
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
.slothBody {
  background-color: #36cfa3;
  font-family: 'Kanit', sans-serif;
}
h1, h2 {
  font-weight: normal;
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
