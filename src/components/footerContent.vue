<template>
  <div>
    <div id="footer-top">
      <div class="container">
        <div class="row">
          <div class="col-2 d-flex align-items-center mx-3" style="height: 160px">
            <img src="..\src\assets\buy-comics-digital-comics.png" alt="" style="width: 40px;">
            <span class="spass">DIGITAL COMICS</span>
          </div>
          <div class="col-2 d-flex align-items-center mx-3" style="height: 160px">
            <img src="..\src\assets\buy-comics-merchandise.png" alt="" style="width: 40px;">
            <span class="spass">DC MERCHANDISE</span>
          </div>
          <div class="col-2 d-flex align-items-center mx-3" style="height: 160px">
            <img src="..\src\assets\buy-comics-subscriptions.png" alt="" style="width: 40px;">
            <span class="spass">SUBSCRIPTIONS</span>
          </div>
          <div class="col-2 d-flex align-items-center mx-3" style="height: 160px; width: 250px; z-index: 10000;">
            <img src="..\src\assets\buy-comics-shop-locator.png" alt="" style="width: 30px;">
            <span class="spass">COMIC SHOP LOCATOR</span>
          </div>
          <div class="col-2 d-flex align-items-center mx-3" style="height: 160px z-index: 10000;">
            <img src="..\src\assets\buy-dc-power-visa.svg" alt="" style="width: 40px; z-index: 10000;">
            <span class="spass">DC POWER VISA</span>
          </div>
        </div>
      </div>
    </div>

    <div id="footer-middle">
      <div class="container">
        <div class="row">
          <div class="col-1 mt-5">
            <h6 class="titles-footer-links">DC COMICS</h6>
            <ul style="margin: 0; padding: 0;">
              <li class="footer-link">  CHARACTERS</li>
              <li class="footer-link">COMICS</li>
              <li class="footer-link">MOOVIES</li>
              <li class="footer-link">TV</li>
              <li class="footer-link">GAMES</li>
              <li class="footer-link">COLLECTIBLES</li>
              <li class="footer-link">VIDEOS</li>
            </ul>
            <h6 class="titles-footer-links mt-3">SHOP DC</h6>
            <ul style="margin: 0; padding: 0;">
              <li class="footer-link">SHOP DC</li>
              <li class="footer-link">SHOP COLLECTIBLES</li>
            </ul>
          </div>
          <div class="col-1 mt-5 mx-3">
            <h6 class="titles-footer-links">DC COMICS</h6>
            <ul style="margin: 0; padding: 0;">
              <li class="footer-link">THERMS OGF USE</li>
              <li class="footer-link">AD CHOISES</li>
              <li class="footer-link">ADVERSTINGS</li>
              <li class="footer-link">JOBS</li>
              <li class="footer-link">SUBSCRIPTIONS</li>
              <li class="footer-link">CPSC CERTIFICATES</li>
              <li class="footer-link">RATINGS</li>
              <li class="footer-link">SHOP HELP</li>
              <li class="footer-link">CONTACT US</li>
            </ul>
          </div>  
          <div class="col-1 mt-5 mx-3">
            <h6 class="titles-footer-links">SITES</h6>
            <ul style="margin: 0; padding: 0;">
              <li class="footer-link">DC</li>
              <li class="footer-link">MAD MAGAZINE</li>
              <li class="footer-link">DC KIDS</li>
              <li class="footer-link">DC UNIVERSE</li>
              <li class="footer-link">DC POWER VISA</li>
              <li class="footer-link">CPSC CERTIFICATES</li>
              <li class="footer-link">RATINGS</li>
              <li class="footer-link">SHOP HELP</li>
              <li class="footer-link">CONTACT US</li>
            </ul>
          </div> 
          <div style="transform: translate(50%, -15%);" id="logo-footer"></div>
        </div>
      </div>
    </div>

    <div id="footer-bottom">
      <div class="container">
        <div class="row">
          <div class="col-1">
            <button type="button" class="btn my-4" style="width: 150px; border-radius: 0; border: 2px solid #0282F9"><span style="color: white;">SIGN-UP NOW!</span></button>
          </div>
          <div class="col-6 d-flex flex-direction-row-reverse">
            <img src="../assets/footer-twitter.png" alt="">
            <img src="../assets/footer-facebook.png" alt="">
            <img src="../assets/footer-youtube.png" alt="">
            <img src="../assets/footer-pinterest.png" alt="">
            <img src="../assets/footer-periscope.png" alt="">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'footerContent',
  props: {
    msg: String
  }
}
</script>


<style scoped lang="scss">
    #footer-top{
        background-color: #0282F9;
    }
    .spass{
      padding-left: 20px;
      color:white;
    }
    #footer-middle{
      width: 100%;
      height: 400px;
      background-image: url(../assets/footer-bg.jpg);
    }
    .titles-footer-links{
      color: white;
    }
    .footer-link{
      font-size: 13px;
      color: grey;
      list-style: none;
      padding-top: 5px;
    }
    #logo-footer{
      width: 600px;
      height: 471px;
      background-image: url(../assets/dc-logo-bg.png);
      background-repeat: no-repeat;
    }
    #footer-bottom{
      width: 100%;
      background-color: #303030;
    }
</style>