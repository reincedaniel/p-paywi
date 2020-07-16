<template>
  <footer
    class="footer"
    :class="{ [`footer-${type}`]: type }"
    :data-background-color="backgroundColor"
  >
    <div class="container">
      
        <div class="row">
          <div class="col-md-4">
             <p>
              <a href="https://www.creative-tim.com">
                <img class="n-logoc" src="img/lg.png" width="210px" alt="" />
              </a> 
              </p>
                <div class="col-md-12 " style="margin-top:-25px">
                  <span style="margin-left:-25px">              
                    <a href="https://www.creative-tim.com">
                      <img class="n-logoc" src="img/Tudo/facebook-01.png" width="100px" alt="" />
                    </a> 
                  </span>
                  <span style="margin-left:-50px">              
                    <a href="https://www.creative-tim.com">
                      <img class="n-logoc" src="img/Tudo/whatsapp-01.png" width="100px" alt="" />
                    </a> 
                  </span> 
                  <span style="margin-left:-50px">              
                    <a href="https://www.creative-tim.com">
                      <img class="n-logoc" src="img/Tudo/twitter-01.png" width="100px" alt="" />
                    </a> 
                  </span> 
                  <span style="margin-left:-50px">              
                    <a href="https://www.creative-tim.com">
                      <img class="n-logoc" src="img/Tudo/insta-01.png" width="100px" alt="" />
                    </a> 
                  </span> 
              </div>
          </div>
          <div class="col-md-4 col-lg-4">
            <div class="content-center brand" style="border:solid thick #bc8810;
            border-width:2px; 
            margin:2px; width:350px; font-family: 'Bebas Neue', cursive;">
              <h1 class="h1-seo ml-3 mt-4" style="font-size:80px">Somos o seu</h1>
              <h3 class="ml-3" style="font-size:29px;  margin-top:-37px">Meio de pagamento mais símples.</h3>
            </div>
            <div class="content-center" style="border:solid thick #ffffff;
              border-width:1px; 
              margin:2px; width:350px; font-family: 'Bebas Neue', cursive; margin-top:10px">
            </div>
            <p style="text-align: center; ">Pagamento fácil e seguro</p>
          </div>
          <div class="col-md-1 col-lg-1">
            <p style="border:solid thick #ffffff;
          border-width:1px; 
           width:1px; height:150px; float:right; "></p>
          </div>
          <div class="col-md-3 col-lg-3">
            <p style="font-weight: bold;">Contactos</p> 
            <span>+244 935 32 74 20</span> <br>
            <span>+244 932 23 06 37</span><br>
            <span>+244 924 94 83 72</span><br>
            <p></p>
            <p style="font-weight: bold;">paywiteam06@gmail.com</p>
          </div>
        </div>


        <!-- <ul>
          <li>
            <div class="">
             <p>
              <a href="https://www.creative-tim.com">
                <img class="n-logoc" src="img/lg.png" width="140px" alt="" />
              </a> 
            </p>  
           <p>
             <img class="n-logoc" src="img/lg.png" width="140px" alt="" />
           </p>

            </div>


          </li>
          <li>
            <a href="https:///presentation.creative-tim.com">
              About Us
            </a>
          </li>
          <li>
            <a href="https:///blog.creative-tim.com">
              Blog
            </a>
          </li>
        </ul> -->
<!--       <div class="copyright">
          <div class="col-md-4 col-lg-4">
            <p>sdmlsdl</p>
          </div>
          <div class="col-md-4 col-lg-4">
            <p>lsdlfjdssjl</p>
          </div>
      </div> -->
    </div>
  </footer>
</template>
<script>
export default {
  props: {
    backgroundColor: String,
    type: String
  },
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
