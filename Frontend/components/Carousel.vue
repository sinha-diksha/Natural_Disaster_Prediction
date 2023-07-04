<script setup lang="ts">

</script>

<template>
  <div class="carousel w-full items-center mt-12">
    <div id="slide1" class="carousel-item relative items-center justify-center w-full">
      <div class="card lg:card-side bg-secondary shadow-xl">
        <figure><img src="../assets/images/tsunami.jpeg" class="object-fill h-96 w-full" alt=""/></figure>
        <div class="card-body">
          <h2 class="card-title">Tsunami Predictor</h2>
          <p>Click the button to on Spotiwhy app.</p>
          <div class="card-actions justify-end">
            <button class="btn btn-primary">Predict</button>
          </div>
        </div>
      </div>


      <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
        <a href="#slide4" class="btn btn-circle">❮</a>
        <a href="#slide2" class="btn btn-circle">❯</a>
      </div>

    </div>

    <div id="slide2" class="carousel-item relative items-center justify-center w-full">
      <div class="card lg:card-side bg-secondary shadow-xl">
        <figure><img src="../assets/images/hurricane.jpeg" class="object-fill h-96 w-100" alt=""/></figure>
        <div class="card-body">
          <h2 class="card-title">Hurricane Predictor</h2>
          <p>Click the button to on Spotiwhy app.</p>
          <div class="card-actions justify-end">
            <button class="btn btn-primary">Predict</button>
          </div>
        </div>
      </div>
      <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
        <a href="#slide1" class="btn btn-circle">❮</a>
        <a href="#slide3" class="btn btn-circle">❯</a>
      </div>
    </div>

    <div id="slide3" class="carousel-item relative items-center justify-center w-full">
      <div class="card lg:card-side bg-secondary shadow-xl">
        <figure><img src="../assets/images/drought.jpeg" class="object-fill h-96 w-100" alt=""/></figure>
        <div class="card-body">
          <h2 class="card-title">Drought Predictor</h2>
          <p>Click the button to on Spotiwhy app.</p>
          <div class="card-actions justify-end">
            <button class="btn btn-primary">Predict</button>
          </div>
        </div>
      </div>

      <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
        <a href="#slide2" class="btn btn-circle">❮</a>
        <a href="#slide4" class="btn btn-circle">❯</a>
      </div>
    </div>

    <div id="slide4" class="carousel-item relative items-center justify-center w-full">
      <div class="card lg:card-side bg-secondary shadow-xl">
        <figure><img src="../assets/images/earthquake.jpeg" class="object-fill h-96 w-100" alt=""/></figure>
        <div class="card-body">
          <h2 class="card-title">Earthquake Predictor</h2>
          <p>Click the button to on Spotiwhy app.</p>
          <div class="card-actions justify-end">
            <button class="btn btn-primary">Predict</button>
          </div>
        </div>
      </div>

      <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
        <a href="#slide3" class="btn btn-circle">❮</a>
        <a href="#slide5" class="btn btn-circle">❯</a>
      </div>
    </div>

    <div id="slide5" class="carousel-item relative items-center justify-center w-full">
      <div class="card lg:card-side bg-secondary shadow-xl">
        <figure><img src="../assets/images/flood.png" class="object-fill h-96 w-100" alt=""/></figure>
        <div class="card-body">
          <h2 class="card-title">Flood Predictor</h2>
          <p>Click the button to on Spotiwhy app.</p>
          <div class="card-actions justify-end">
            <button class="btn btn-primary">Predict</button>
          </div>
        </div>
      </div>

      <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
        <a href="#slide4" class="btn btn-circle">❮</a>
        <a href="#slide1" class="btn btn-circle">❯</a>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>