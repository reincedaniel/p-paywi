<template>
  <div>
    <div class="page-header" filter-color="orange">
      <parallax
        class="page-header-image"
        style="background-image:url('img/c.jpg')"
      >
      </parallax>
      <div class="container">
        
        <div class="content-center brand" style="border:solid thick #bc8810;
          border-width:2px; 
          margin:2px; width:350px; font-family: 'Bebas Neue', cursive;">
          <h1 class="h1-seo mt-4" style="font-size:80px">Somos o seu</h1>
          <h3 class="" style="font-size:29px;  margin-top:-37px">Meio de pagamento mais símples.</h3>
          
        </div>
        <div class="content-center" style="border:solid thick #ffffff;
          border-width:1px; 
          margin:2px; width:200px; font-family: 'Bebas Neue', cursive; margin-top:130px">
        </div>
        <h6 class="category category-absolute" style="color:red">
          Proposta: by Enzo Daniel Carlos / Aguardando feeds!
        </h6>
      </div>
    </div>
    <!-- <div class="main">
      <div class="section section-images">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <div class="hero-images-container">
                <img src="img/hero-image-1.png" alt="" />
              </div>
              <div class="hero-images-container-1">
                <img src="img/hero-image-2.png" alt="" />
              </div>
              <div class="hero-images-container-2">
                <img src="img/hero-image-3.png" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <basic-elements></basic-elements>
    <navigation></navigation>
    <tabs-section></tabs-section>
    <progress-pagination></progress-pagination>
    <notifications></notifications>
    <typography></typography>
    <javascript-components></javascript-components>
    <carousel-section></carousel-section>
    <nucleo-icons-section></nucleo-icons-section>
    <div class="section">
      <div class="container text-center">
        <div class="row justify-content-md-center">
          <div class="col-md-12 col-lg-8">
            <h2 class="title">Completed with examples</h2>
            <h5 class="description">
              The kit comes with three pre-built pages to help you get started
              faster. You can change the text and images and you're good to go.
              More importantly, looking at them will give you a picture of what
              you can built with this powerful Bootstrap 4 ui kit.
            </h5>
          </div>
        </div>
      </div>
    </div>
    <signup-form></signup-form>
    <examples-section></examples-section>
    <download-section></download-section> -->
  </div>
</template>
<script>
import { Parallax } from '@/components';
/* import BasicElements from './components/BasicElementsSection';
import Navigation from './components/Navigation';
import TabsSection from './components/Tabs';
import ProgressPagination from './components/ProgressPagination';
import Notifications from './components/Notifications';
import Typography from './components/Typography';
import JavascriptComponents from './components/JavascriptComponents';
import CarouselSection from './components/CarouselSection';
import NucleoIconsSection from './components/NucleoIconsSection';
import SignupForm from './components/SignupForm';
import ExamplesSection from './components/ExamplesSection';
import DownloadSection from './components/DownloadSection'; */

export default {
  name: 'index',
  bodyClass: 'index-page',
  components: {
    Parallax,
/*     BasicElements,
    Navigation,
    TabsSection,
    ProgressPagination,
    Notifications,
    Typography,
    JavascriptComponents,
    CarouselSection,
    NucleoIconsSection,
    SignupForm,
    ExamplesSection,
    DownloadSection */
  }
};
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
</style>