<template>
      <div id="carouselExampleDark" class="carousel carousel-dark slide">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="10000">
      <img src="../assets/img/SC.png" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>First slide label</h5>
        <p>Some representative placeholder content for the first slide.</p>
      </div>
    </div>
    <div class="carousel-item" data-bs-interval="2000">
      <img src="../assets/img/guru.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Second slide label</h5>
        <p>Some representative placeholder content for the second slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="../assets/img/kepsek2.jpg" class="img" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Third slide label</h5>
        <p>Some representative placeholder content for the third slide.</p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<div class="card" style="width: 20rem;">
  <img src="../assets/img/kurniawan.png" class="card-img-center" alt="...">
  <div class="card-body">
    <p class="card-text"><h4>Kepala Sekolah</h4></p>
  </div>
</div>
  <div class="row">
        <h3>JURUSAN</h3>
        <div class="col-6">
            <img src="~/assets/img/tjkt.jpg" alt="">
            <img src="~/assets/img/pplg.jpg" alt="">
            <img src="~/assets/img/tbsm.jpg" alt="">
            <img src="~/assets/img/dkv.jpg" alt="">
            <img src="~/assets/img/toi.jpg" alt="">
        </div> 
    </div>
</template>
<style>
.carousel-item img{
  height: 90vh;
  width: 100vw;
}
.card{
  margin: 400px;
  display: flex;
  justify-content: center;
}
.row{
  text-align: center ;
}
.image-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr); 
  grid-template-rows: repeat(2, auto); 
  gap: 10px; 
}

.image-grid img {
  width: 100%;
  height: auto;
}
</style>