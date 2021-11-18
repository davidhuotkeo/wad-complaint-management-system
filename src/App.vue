<template>
  <div id="app">
    <nav class="navbar navbar-expand navbar-light">
      <div class="container">
        <router-link :to="{ name: 'Home' }" class="nav-home">Complainto</router-link>
        <div class="menu">
          <ul>
            <li>
              <router-link :to="{ name: 'About'}" class="nav-login">Login</router-link>
            </li>
            <li>
              <router-link :to="{ name: 'About'}" class="nav-signup">Sign Up</router-link>
            </li>
          </ul>  
        </div>  
      </div>
    </nav>
  </div>
  <router-view/>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  background-color: #f7ebe5;
}
.app {
  width: 100%;
  height: 100%;
}
.nav-home{
  font-style: bold;
  font-size: 28pt;
  padding-left: 30px;
  color: salmon;
  text-decoration: none;
}
.nav-home:hover{
  color: salmon;
}
.menu ul{
  display: inline-flex;
  margin: 50px;
}
.menu ul li{
  align-self: center;
  list-style: none;
  margin: 0 20px;
  color: whitesmoke;
  cursor: pointer;
}
.nav-login{
  top: 40px;
  text-decoration: none;
  color: black;
}
.nav-login:hover{
  color: black;
}
.nav-signup{
  top: 40px;
  text-decoration: none;
  color: white;
  border: none;
  border-radius: 25px;
  padding: 5px 10px;
  background-color: salmon;
}
.nav-signup:hover{
  color: white;
}
</style>

