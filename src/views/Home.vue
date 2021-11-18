<template>
  <div class="home">
    <div class="banner">
      <div class="banner-image">
        <img src="../assets/home_img.png">
      </div>
      <div class="banner-text">
        <h1>Submit Us Your Complaints</h1>
        <p>If you have any complaints, we are glad to help. Submit any problems you may have to our team and we will look into the matter ASAP!</p>
      </div>
      <div class="btn">
        <router-link :to="{ name: 'Home'}" class="submit-btn">Submit</router-link>
      </div>
    </div>
  </div>
</template>

<script>

</script>

<style>
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
