<template>
  <f7-page>
    <f7-navbar title="3D Cube" back-link="Back"></f7-navbar>
    <div data-effect="cube" class="swiper-container swiper-init demo-swiper demo-swiper-cube">
      <div class="swiper-wrapper">
        <div style="background-image:url(http://lorempixel.com/800/800/people/1/)" class="swiper-slide">Slide 1</div>
        <div style="background-image:url(http://lorempixel.com/800/800/people/2/)" class="swiper-slide">Slide 2</div>
        <div style="background-image:url(http://lorempixel.com/800/800/people/3/)" class="swiper-slide">Slide 3</div>
        <div style="background-image:url(http://lorempixel.com/800/800/people/4/)" class="swiper-slide">Slide 4</div>
        <div style="background-image:url(http://lorempixel.com/800/800/people/5/)" class="swiper-slide">Slide 5</div>
        <div style="background-image:url(http://lorempixel.com/800/800/people/6/)" class="swiper-slide">Slide 6</div>
        <div style="background-image:url(http://lorempixel.com/800/800/people/7/)" class="swiper-slide">Slide 7</div>
        <div style="background-image:url(http://lorempixel.com/800/800/people/8/)" class="swiper-slide">Slide 8</div>
        <div style="background-image:url(http://lorempixel.com/800/800/people/9/)" class="swiper-slide">Slide 9</div>
      </div>
    </div>
  </f7-page>
</template>
<script>
  import { f7Navbar, f7Page } from 'framework7-vue';

  export default {
    components: {
      f7Navbar,
      f7Page,
    },
  };
</script>
