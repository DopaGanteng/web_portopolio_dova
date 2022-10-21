<script setup></script>

<template>
<div class="container">
    <div class="row">
      <div class="col-md text-center mt-4">
        <div class="profile">
          <img src="../assets/profile.png" alt="" class="rounded-circle" />
        </div>
      </div>
    </div>
  </div>
  <div class="container">
    <div class="row">
      <div class="col-md m-auto text-center mt-5">
        <div class="deskripsi_diri">
          <h4>Hello, My name is Dova Aditya! Welcome!</h4>
          <p>
            I'm a Student from Institut Bisnis dan Informatika Kosgoro 1957
            I'm from Jakarta
            I'm a part of Stechoq Robotika Indonesia as a Study Independent activity
          </p>
      </div>
    </div>
  </div>
</div>
<div class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div class="card h-100">
      <img src="../assets/projek1.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Project 1</h5>
        <p>Membuat web Portopolio pribadi</p>
        <p class="card-text">Berikut adalah hasil project saya selama belajar basic web programming membuat Portopolio sederhana.</p>
        <a 
      href="https://dopaganteng.github.io/Basic-website-dova.github.io/home.html"
      class="btn btn-outline-primary"
      >More</a>
      </div>
      <div class="card-footer">
        <small class="text-muted">Last updated 3 mins ago</small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="../assets/projek2.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Project 2</h5>
        <p>Membuat form registrasi sederhana</p>
        <p class="card-text">Berikut adalah project saya selama belajar basic web programming juga membuat sebuah web form registrasi sederhana.</p>
        <a 
      href="https://dopaganteng.github.io/Dova_Aditya/"
      class="btn btn-outline-primary"
      >More</a>
      </div>
      <div class="card-footer">
        <small class="text-muted">Last updated 3 mins ago</small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="../assets/project3.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Project 3</h5>
        <p>Membuat kerkulator sederhana</p>
        <p class="card-text">Berikut ini adalah hasil self learning saya belajar node js</p>
        <a 
      href="https://github.com/DopaGanteng/kalkulator_nodejs"
      class="btn btn-outline-primary"
      >More</a>
      </div>
      <div class="card-footer">
        <small class="text-muted">Last updated 3 mins ago</small>
      </div>
    </div>
  </div>
</div>

<div></div>
</template>

<style>
.deskripsi_diri p {
  line-height: 30px;
}
.card img {
  width: 200px;
  margin: auto;
}
.jumbotron {
  background-color: darkgoldenrod;
  height: 180px;
  border-radius: 30px;
}
</style>