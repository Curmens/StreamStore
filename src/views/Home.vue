<template>
  <div class="home">
    <div class="hero-banner">
      <!-- NAVBAR -->
      <div class="navbar row w-100">
        <div class="logo nav-logo col-2">
          <img src="@/assets/images/logo.png" alt="">
        </div>
        <div class="nav-list col-10">
          <ul class="nav-items">
            <li class="nav-item">Home</li>
            <li class="nav-item">About Us</li>
            <li class="nav-item">Pricing</li>
            <li class="nav-item">Contact Us</li>
            <li class="nav-btn btn">Sign Up</li>
          </ul>
        </div>
      </div>
      <!-- HERO BANNER  -->
      <div class="hero-content row h-100">
        <div class="hero-img col-5 h-100">
          <img src="@/assets/images/clientadvert.png" class="h-100" alt="">
        </div>
        <div class="col-7 h-100">
          <div class="hero-info h-100">
            <div class="header-caption"><h1>Your Perfect <br>online music <br>store <span>Reloaded</span></h1></div>
            <p class="additional-info text-white">Quaerat et natus aliquid facere quam soluta incidunt officiis libero ut! Et explicabo nesciunt aliquid iure nam necessitatibus repellat reiciendis? Tenetur, eligendi.</p>
            <p class="text-white">Coming Soon On</p>
            <div class="get__download row">
              <div class="download-btn btn col-6"><i class="fa fa-apple"></i> APP STORE</div>
              <div class="download-btn btn-2 btn col-6"><i class="fab fa-google-play"></i> PLAYSTORE</div>
            </div>
          </div>
          </div>
      </div>
    </div>
    <!-- SECTION ONE  -->
    <section class="info-col">
      <div class="title__box mt-5">
        <h1 class="title">How it Works</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit ipsa amet consequatur? <br> Lorem ipsum dolor sit amet.</p>
      </div>
      <form action="" class="form mb-5">
        <input type="email" class="email-input">
        <button class="btn sub-btn">Subscribe Here</button>
      </form>
    </section>
    <!-- PROFILE SECTION  -->
    <section class="artist-info row w-100">
      <div class="col-md-6">
        <div class="sec-title">
          <h1>Listen to your favorite Music Artist</h1>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Porro incidunt illo possimus delectus laboriosam architecto neque tenetur ea praesentium ipsum.</p>
        </div>
      </div>
      <div class="col-md-6 img-container">
        <img src="@/assets/images/artist1.png" alt="" class="w-50 artist-image">
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld,
  },
};
</script>

<style scoped>
.img-container{
  text-align: center;
  /* margin: auto; */
}

.title__box{
  text-align: center;
}

.title{
  font-size: 40px;
  font-weight: 600;
}

.get__download{
  margin-left: 0px;
}

.hero-content{
  padding-top: 5rem;
}

.download-btn{
  background-color: rgba(246, 132, 49, 1);
  color: #0c0101;
  font-size: 16px;
  font-weight: 600;
  width: 15rem;
  margin-right: 15px;
  border-radius: 6px;
}

.btn-2{
  background-color: transparent;
  border: 1.9px solid rgba(246, 132, 49, 1);
  color: #fefefe;
  /* content: 'f3ab'; */
}

.hero-img{
  text-align: right;
}

.hero-banner{
  overflow: hidden;
  width: 100%;
  height: 85vh;
  background-color: #1F0F33;
}

.nav-item{
  color: white;
  list-style: none;
  margin: auto;
}

.nav-item:hover{
  color: rgba(246, 132, 49, 1);
  cursor: pointer;
}

.nav-btn{
  color: #1F0F33;
  background-color: rgba(246, 132, 49, 1);
}

.nav-items{
  display: flex;
  flex-direction: row;
  place-content: space-evenly;
}

.nav-list{
  width: 35rem;
}

.header-caption > h1{
  line-height: 65px;
  color: #fefefe;
  font-size: 4.5rem;
  font-weight: 600;
}

.header-caption > h1 > span{
  color: rgba(246, 132, 49, 1);
}

.hero-info{
  text-align: left;
  display: grid;
  place-content: center;
  max-width: 40rem;
}

.navbar{
  padding: 10px 40px;
  position: absolute;
}

.sub-btn{
  background-color: rgba(246, 132, 49, 1);
  color: #000008;
  border-radius: 6px;
  text-transform: uppercase;
  font-weight: 600;
}

.email-input{
  border-radius: 6px;
  border: 1.5px solid #8b8b8b8f;
  height: 40px;
  width: 27rem;
  margin-right: 1rem;
}

input:focus{
  outline: none;
}

form{
  display: flex;
  place-content: center;
}

section{
  padding: 0 5rem;
}

.sec-title h1{
  font-weight: 600;
}

.sec-title{
  width: 60%;
  margin: 4rem auto;
}
</style>
