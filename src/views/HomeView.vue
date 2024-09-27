<template>
  <div class="home">
    <h1>Hi, my name is Irina Zivitz</h1>
  </div>
  <h5 class="text-wrap ms-20 mt-3">
    I'm a  frontend developer.  Check out my recent work and get in touch to chat about potential projects. 
  </h5>
  <hr>
  <a href="https://charming-crisp-9672b3.netlify.app">
      <h4> MyTide app</h4>
  </a>
  
  <div class="d-flex align-items-center">
      <a href="https://charming-crisp-9672b3.netlify.app">
        <img class="rounded float-image ms-3 mt-3 mb-3" src="../assets/tideAppImage.jpg" alt="tideApp image"> 
      </a>
     
      <div class="ms-5 me-3">
        <p>
          I live near the Atlantic Ocean and often need to know the tide, 
          so I know where to put my beach chair or should I promise my 5yo tidal 
          pools or not. Of course, most people use tide info for much serious purpose, 
          like surfing or fishing or actually navigating boats. I designed this 
          single-purpose app to be informative and minimalistic, to leave more 
          mindspace for fun and actual waves.
        </p>  
        <div class="custom-button"> Vue.js</div>
        <div class="custom-button"> JavaScript</div>
        <div class="custom-button"> CSS</div>
        <div class="custom-button"> HTML</div>
        <div class="mt-3">
            <a href="https://charming-crisp-9672b3.netlify.app"> deployed site</a> | 
            <a href="https://github.com/irinazivitz/tide-app"> GitHub</a> 
  
        </div>
      </div>   
  </div>
  
</template>

<script>

</script>

<style scoped>
.float-image{
  width:400px;
  box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.3);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.custom-button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #f8f9fa; /* Light background */
  color: #000; /* Text color */
  border-radius: 5px; /* Rounded corners */
  border: 1px solid #ced4da; /* Border color */
  text-align: center;
  cursor: default; /* Default cursor, no hand pointer */
  font-size: 16px;
  margin: 5px; /* Add space between "buttons" */
  text-decoration: none;
}
a {
  color:rgb(55, 112, 70);
  text-decoration: none;
}


</style>
