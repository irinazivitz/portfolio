<template>
  <nav>
    <router-link to="/">Portfolio</router-link> |
     <router-link to="/resume"> Resume</router-link> |
    <a href="https://www.linkedin.com/in/irinazivitz"> LinkedIn</a> | 
    <a href="https://github.com/irinazivitz"> GitHub</a> 
  </nav>
  <router-view/> 
 
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: #5db58d;
}
</style>
