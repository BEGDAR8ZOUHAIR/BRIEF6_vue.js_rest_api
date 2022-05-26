<template>
<NavBar />
  <div class="galerie">
        <img src="../assets/images/description-1.svg" alt="">
        <img src="../assets/images/booking-image-white.svg" alt="">
      
    </div>
    <div class="main">
        <!-- <h2>Exceptional</h2> -->
        <div class="title">Dentair</div>
        <p>Trouvez votre dentiste et prenez un rendez-vous.
        C'est gratuit, simple, et disponible 24/7 <br>Optimisez 
        l'activité de votre cabinet ou clinique dentaire grâce aux merveilles du Digital.</p>
    </div>
    <div class="galerie">
        <img src="../assets/images/1.svg" alt="">
        <img src="../assets/images/2.svg" alt="">
        <img src="../assets/images/3.svg" alt="">
        
      
    </div>
    <Footer />
</template>




<script>

import NavBar from '../components/NavBar.vue';
import Footer from '../components/Footer.vue';

export default{
  name: "HomeView",
  components: {
    NavBar,
    Footer
  }

}


</script>


<style lang="scss">

/* galerie  */


.galerie {
    height: auto;
    width: 100%;
    display: grid;
    grid-template-columns: auto auto auto;
}

.galerie img {
    height: 100%;
    width: 100%;
    background-color: white;
    text-align: center;
}

/* main */

.main{
    padding: 0 10% 0 10%;
    margin-top: 2%;
    margin-bottom: 3%;
}
.main p{
    margin-top: 1%;
    color: #a6a6a6;
    line-height: 30px;
}
.main .title{
    margin-top: 1%;
    font-family: 'Parisienne';
    font-size: 83px;
    color: #68d391;
}



</style>
