<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Navbar from './components/Navbar.vue'
import ImageCarousel from './components/ImageCarousel.vue'
</script>

<template>
  <div class="flex flex-col h-screen bg-base-100 static">
    <button class="btn btn-secondary absolute transform -translate-x-3/4 left-5  ">Bottom Right</button>
    <div class="grid grid-cols-3 gap-2 resize-y">
      <div class="col-span-1 bg-base-200 flex flex-col h-screen">
        <div class="carousel carousel-center carousel-vertical container m-auto">
          <div class="carousel-item relative my-0.5 w-full">
            <img src="https://api.lorem.space/image/car?8B7BCDC2" class="w-full  object-contain pl-2"
              alt="Tailwind CSS Carousel component" />
          </div>
          <div class="carousel-item relative my-0.5 w-full">
            <img src="https://api.lorem.space/image/game?500B67FB" class="w-full  object-contain pl-2"
              alt="Tailwind CSS Carousel component" />
          </div>
          <div class="carousel-item relative my-0.5 w-full">
            <img src="https://api.lorem.space/image/car?500B67FC" class="w-full  object-contain pl-2"
              alt="Tailwind CSS Carousel component" />
          </div>
          <div class="carousel-item relative my-0.5 w-full">
            <img src="https://api.lorem.space/image/car?500B67CR" class="w-full  object-contain pl-2"
              alt="Tailwind CSS Carousel component" />
          </div>
        </div>
      </div>
      <div class="col-span-2 bg-neutral flex flex-col h-screen">
        <div class=" carousel carousel-center container  m-auto">
          <div id="slide1" class="carousel-item relative w-full">
            <!-- Object-contain allows the image to be shown with its full size -->
            <img src="https://api.lorem.space/image/car?8B7BCDC2" class="w-full  object-contain"
              alt="Tailwind CSS Carousel component" />
            <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
              <a href="#slide4" class="btn btn-circle">❮</a>
              <a href="#slide2" class="btn btn-circle">❯</a>
            </div>
          </div>
          <div id="slide2" class="carousel-item relative w-full">
            <img src="https://api.lorem.space/image/game?500B67FB" class="w-full  object-contain"
              alt="Tailwind CSS Carousel component" />
            <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
              <a href="#slide1" class="btn btn-circle">❮</a>
              <a href="#slide3" class="btn btn-circle">❯</a>
            </div>
          </div>
          <div id="slide3" class="carousel-item relative w-full">
            <img src="https://api.lorem.space/image/car?500B67FC" class="w-full  object-contain"
              alt="Tailwind CSS Carousel component" />
            <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
              <a href="#slide2" class="btn btn-circle">❮</a>
              <a href="#slide4" class="btn btn-circle">❯</a>
            </div>
          </div>
          <div id="slide4" class="carousel-item bg-contain relative w-full">
            <img src="https://api.lorem.space/image/car?500B67CR" class="w-full  object-contain"
              alt="Tailwind CSS Carousel component" />
            <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
              <a href="#slide3" class="btn btn-circle">❮</a>
              <a href="#slide1" class="btn btn-circle">❯</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
</style>
