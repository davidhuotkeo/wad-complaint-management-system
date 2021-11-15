<template>
  <div id="app">
    <nav class="navbar navbar-expand navbar-light">
      <div class="container">
        <a href="#" class="nav-home">Complainto</a>
        <div class="menu">
          <ul>
            <li>
              <a href="#" class="nav-login">Login</a>
            </li>
            <li>
              <a href="#" class="nav-signup">Sign Up</a>
            </li>
          </ul>  
        </div>  
      </div>
    </nav>
    <div class="banner">
      <div class="banner-image">
        <img src="./assets/home_img.png">
      </div>
      <div class="banner-text">
        <h1>Submit Us Your Complaints</h1>
        <p>If you have any complaints, we are glad to help. Submit any problems you may have to our team and we will look into the matter ASAP!</p>
      </div>
      <div class="btn">
        <a href="#" class="submit-btn">Submit</a>
      </div>
    </div>
  </div>
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
.banner{
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  margin: auto;
}
.banner-image{
  align-items: center;
  align-self: center;
}
.banner-image img{
  height: 50%;
  max-width: 100%;
  width: 400px;
}
.banner-text{
  padding-top: 10px;
  max-width: 100%;
 
  width: 500px;
}
.banner-text h1{
  font-size: 35px;
  color: black;
  width: 100%;
  text-align: center;
}
.banner-text p{
  font-size: 15px;
  color:gray;
  width: 100%;
  text-align: center;
  padding: 0px 50px 0px 50px;
}
.submit-btn{
  border: none;
  color: white;
  background-color: salmon;
  text-decoration: none;
  text-align: center;
  padding: 5px 10px;
  border-radius: 25px;
}
.submit-btn:hover{
  color: white;
}
</style>
