<template>
  <div>
    <div id="header-top">
    </div>
    <div class="container">
      <div class="row" id="header-bottom" >
        <div class="col-4 d-flex align-items-center">
          <img src="..\src\assets\dc-logo.png" alt="">
        </div>
        <div class="col-8 d-flex">
          <div class="link-header" href="#"><span>CHARACTERS</span></div>
          <div class="link-header" href="#"><span>COMICS</span></div>
          <div class="link-header" href="#"><span>MOOVIES</span></div>
          <div class="link-header" href="#"><span>TV</span></div>
          <div class="link-header" href="#"><span>GAMES</span></div>
          <div class="link-header" href="#"><span>COLLECTIBLES</span></div>
          <div class="link-header" href="#"><span>VIDEOS</span></div>
          <div class="link-header" href="#"><span>FUNS</span></div>
          <div class="link-header" href="#"><span>NEWS</span></div>
          <div class="link-header" href="#"><span>SHOP</span></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'headerContent',
  props: {
    msg: String
  }
}
</script>


<style scoped lang="scss">
  #header-top{
    width: 100%;
    height: 40px;
    background-color: black;
  }
  #header-bottom{
    width: 100%;
    height: 130px;
  }
  #logo-header{
    
  }
  .link-header {
    display: flex;
    align-items: center;
    padding-left: 15px;
    padding-right: 15px;
  }
</style>
