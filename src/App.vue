<template>
  <div id="app">
    <div id="nav">
      <ul>
        <li class="navbar-header">
          <router-link to="/">Welcome Map Annecy</router-link>
        </li>
        <li style="float:right">
          <router-link to="/infos">Infos</router-link>
        </li>
      </ul>
    </div>
    <router-view />
  </div>
</template>

<style>
html,
body,
#app {
  height: 100%;
  margin: 0;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

  display: flex;
  flex-direction: column;
  flex-flow: column;
}

#nav {
  padding: 20px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

#nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
}

#nav li {
  float: left;
}

a {
  font-weight: bold;
  color: #2c3e50;
  display: block;
  padding: 0 5px;
  text-align: center;
  text-decoration: none;
}

a:hover:not(.active) {
  color: #42b983;
}

#nav li a:hover:not(.active) {
  background-color: #ebebeb;
}
</style>
