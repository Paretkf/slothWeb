<template>
    <nav class="navbar is-transparent slothBody">
        <div class="navbar-brand">
            <a class="navbar-item">
            <img src="../assets/weblogo.png">
            </a>
            <a class="navbar-item" href="https://bulma.io/">
                    SLOTH Web-Creation
            </a>
            <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>

        <div id="navbarExampleTransparentExample" class="navbar-menu">
            <div class="navbar-start">
            </div>
            <div class="navbar-end">
                <a  class="navbar-item">
                     ABOUT
                </a>
                <a  class="navbar-item">
                     CONTACT
                </a>
            </div>
        </div>
    </nav>
</template>

<script>
document.addEventListener('DOMContentLoaded', function () {
  var $navbarBurgers = Array.prototype.slice.call(document.querySelectorAll('.navbar-burger'), 0)
  if ($navbarBurgers.length > 0) {
    $navbarBurgers.forEach(function ($el) {
      $el.addEventListener('click', function () {
        var target = $el.dataset.target
        var $target = document.getElementById(target)
        $el.classList.toggle('is-active')
        $target.classList.toggle('is-active')
      })
    })
  }
})
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
  background-color: #2c3e50;
  color: white;
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
