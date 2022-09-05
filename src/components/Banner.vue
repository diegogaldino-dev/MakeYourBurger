<template>
  <div id="main-banner">
    <h1>Make Your Burger</h1>
  </div>
  
</template>
<script>
  export default{
    nome: 'Banner'
  }

</script>

<style scoped>

#main-banner {
    background-image: url("../../public/img/burger.jpg");
    background-position: 0 -150px;
    background-size: cover;
    background-repeat: no-repeat;
    height: 450px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }

  #main-banner h1 {
    color: #fff;
    text-align: center;
    font-size: 50px;
    background-color: #222;
    padding: 20px 40px;
  }


  @media (max-width : 980px){
    #main-banner h1{
      font-size: 40px;
    }

    #main-banner{
      height: 400px;
    background-position: 0 -130px;
    }
  }

  @media (max-width : 845px){
    #main-banner h1{
      margin-bottom: 50px
    }

    #main-banner{
      height: 400px;
    }
    
  }

  @media (max-width : 820px){
    #main-banner h1{

      font-size: 38px;
      margin-bottom: 53px
    }

    #main-banner {
    background-position: 0 -120px;
    }
    
  }

  @media (max-width : 800px){
    #main-banner h1{
      font-size: 35px;
      margin-bottom: 70px
    }

    #main-banner {
    background-position: 0 -110px;
    }
    
  }

  @media (max-width : 780px){
    #main-banner h1{
      font-size: 33px;
      margin-bottom: 75px
    }
    #main-banner{
      height: 380px;
    }
    
  }

  @media (max-width : 750px){
    #main-banner h1{
      margin-bottom: 125px
    }

    #main-banner{
      height: 380px;
    }
    
  }

  @media (max-width : 710px){
    #main-banner h1{
      font-size: 30px;
      margin-bottom: 90px
    }

    #main-banner{
      height: 350px;
    background-position: 0 -100px;
    }
    
    
  }

  @media (max-width : 690px){

    #main-banner h1{
      margin-bottom: 85px
    }

    #main-banner{
      height: 330px;
    }   
  }


  @media (max-width : 650px){
    #main-banner h1{
      margin-bottom: 82px
    }

    #main-banner{
      height: 300px;
    }

  }

  @media (max-width : 650px){
    #main-banner h1{
      font-size: 25px;
    }
    #main-banner {
    background-position: 0 -90px;
    }
  }

  @media (max-width : 600px){
    #main-banner {
    background-position: 0 -80px;
    }
  }

  @media (max-width: 570px){
    #main-banner h1{
      font-size: 22px;
    }
  }

  @media (max-width: 520px){
    #main-banner h1{
      font-size: 20px;
    }

  }

  @media (max-width: 485px){
    #main-banner h1{
      font-size: 18px;
    }

    #main-banner {
    background-position: 0 -70px;
    }

  }
  @media (max-width: 460px){
    #main-banner h1{
      font-size: 15px;
    }

    #main-banner {
    background-position: 0 -65px;
    height: 250px;
    }

  }

  @media (max-width: 420px){
    #main-banner h1{
      font-size: 15px;
    }

    #main-banner {
    background-position: 0 -60px;
    height: 220px;
    }

  }

  @media (max-width: 390px){
    #main-banner h1{
      font-size: 13px;
    }

    #main-banner {
    background-position: 0 -55px;
    height: 210px;
    }

  }

  @media (max-width: 365px){
    #main-banner h1{
      font-size: 10px;
    }

    #main-banner {
    background-position: 0 -50px;
    height: 200px;
    }

  }


  @media (max-width: 340px){
    #main-banner h1{
      position: relative;
      margin-bottom: 50px;
      font-size: 10px;
      display: flex;
    }

    #main-banner{
      font-size: 15px;
      width: 110%;
      height: 250px;
      background-position: 0 -40px;
    }

  }



  @media (min-width: 1440px){
    #main-banner{
    height: 550px;
    background-size: 1440px, 10px;
    background-position: 0 -200px;

    }

  }
  @media (min-width: 1910px){
    #main-banner{
    height: 750px;
    background-size: 1910px, 70px;
    background-position: 0 -280px;

    }

  }



</style>
