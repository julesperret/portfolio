<template>
  <div id="app">
    <div class="nav">
      <p>le logo</p>
      <ul>
        <li><a href="">accueil</a></li>
        <li><a href="">qui suis je ?</a></li>
        <li><a href="">projets</a></li>
        <li><a href="">contact</a></li>
      </ul>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
