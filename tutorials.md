---
layout: page
title: "Tutorial"
---

<style>
  .div{
    position: relative;
    float: right;
    right:200px;
    margin-top: 100px;
    margin-right: 500px;
    width: 700px;
    height: 500px;
   }
</style>
<body >
  <div id="div"> 
    <button name="button">Click me</button> 
    <center>
     <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
     <div id="carouselExampleControlsNoTouching" class="carousel slide" data-bs-touch="false" data-bs-interval="false">
        <div class="carousel-inner">
          <div class="carousel-item active">
          <p><img style="float: left; margin-right: 500px;" src="/photos/logo1.png" height = 240px width = 240px></p>
          <br/><br/>
          </div>
          <div class="carousel-item">
          <p><img style="float: left; margin-right: 500px;" src="/photos/logo2.png" height = 240px width = 240px></p>
          <br/><br/>
          </div>
          <div class="carousel-item">
          <p><img style="float: left; margin-right: 500px;" src="/photos/logo3.png" height = 240px width = 240px></p>
          <br/><br/>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </center>  
  </div>
</body>
</html>


