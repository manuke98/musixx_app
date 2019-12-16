<template>
  <div id="app">
    <!-- <div id="nav"> 
      <router-link to="/">Home</router-link> |
      <router-link to="/tracks">Tracks</router-link> |
      <router-link to="/albums">Albums</router-link> |
      <router-link to="/artists">Artists</router-link>
    </div> -->
    <section class="hero is-warning">
  <!-- Hero head: will stick at the top -->
  <div class="hero-head">
    <header class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <a class="navbar-item">
            <img src="../public/music.png" alt="Logo">
          </a>
          <span class="navbar" data-target="navbarMenuHeroC">
            <span></span>
            <span></span>
            <span></span>
          </span>
        </div>
        <div id="navbarMenuHeroC" class="navbar-menu">
          <div class="navbar-start">
            <a class="navbar-item is-active">
              <router-link to="/">Home</router-link>
            </a>
            <a class="navbar-item">
              <router-link to="/tracks">Tracks</router-link>
            </a>
            <a class="navbar-item">
              <router-link to="/albums">Albums</router-link>
            </a>
            <a class="navbar-item">
              <router-link to="/artists">Artists</router-link>
            </a>
            
          </div>
        </div>
      </div>
    </header>
  </div>

</section>
    <router-view/>
  </div>
    
 
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
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
