<template>
  <navbar
    position="fixed"
    type="primary"
    :transparent="transparent"
    :color-on-scroll="colorOnScroll"
    menu-classes="ml-auto"
  >
    <template>
      <router-link v-popover:popover1 class="brand" to="/">
        <img class="n-logoc" src="img/lg.png" width="140px" alt="" />

      </router-link>
      <el-popover
        ref="popover1"
        popper-class="popover"
        placement="bottom"
        width="200"
        trigger="hover"
      >
        <div class="popover-body">
          Paywi
        </div>
      </el-popover>
    </template>
    <template slot="navbar-menu">
      <li class="nav-item">
        <a
          class="nav-link"
          href="#"
          
        >
          <p class="xp" style="font-size:17px">SOLUÇÕES</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          href="#"
          
        >
          <p class="xp" style="font-size:17px">SOBRE NÓS</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          href="#"
          
        >
          <p class="xp" style="font-size:17px">COMO FUNCIONA</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          href="#"
          
        >
          <p class="xp" style="font-size:17px">SUPORTE</p>
        </a>
      </li>
      
      <!-- <li class="nav-item">
        <a
          class="nav-link"
          href="#"
          
        >
          <i class="now-ui-icons arrows-1_cloud-download-93"></i>
          <p>Download</p>
        </a>
      </li>
      <drop-down
        tag="li"
        title="Components"
        icon="now-ui-icons design_app"
        class="nav-item"
      >
        <nav-link to="/">
          <i class="now-ui-icons business_chart-pie-36"></i> All components
        </nav-link>
        <a
          href="https://demos.creative-tim.com/vue-now-ui-kit/documentation"
          
          class="dropdown-item"
        >
          <i class="now-ui-icons design_bullet-list-67"></i> Documentation
        </a>
      </drop-down>
      <drop-down
              tag="li"
              title="Examples"
              icon="now-ui-icons design_image"
              class="nav-item"
      >
        <nav-link to="/landing">
          <i class="now-ui-icons education_paper"></i> Landing
        </nav-link>
        <nav-link to="/login">
          <i class="now-ui-icons users_circle-08"></i> Login
        </nav-link>
        <nav-link to="/profile">
          <i class="now-ui-icons users_single-02"></i> Profile
        </nav-link>
      </drop-down> -->
      <li class="nav-item">

        <button type="button" class="nav-link btn shadow-lg bg-red" style="border-radius:0; background-color:#bc8810">ENTRAR</button>
      </li>

      <li class="nav-item"  style="font-size:30px">
        <a
          class="nav-link"
          rel="tooltip"
          title="Follow us on Instagram"
          data-placement="bottom"
          href="#"
          
        >
          <i class="far fa-user-circle"></i>
          <!-- <p class="d-lg-none d-xl-none">Instagram</p> -->
        </a>
      </li>
<!-- 
      <li class="nav-item">
        <a
          class="nav-link"
          href="#"
          
        >
          <i class="now-ui-icons users_circle-08"></i>
          <p>SOBRE NÓS</p>
        </a>
      </li> -->
    </template>
  </navbar>
</template>

<script>
import {Navbar} from '@/components';
import { Popover } from 'element-ui';
export default {
  name: 'main-navbar',
  props: {
    transparent: Boolean,
    colorOnScroll: Number
  },
  components: {
    Navbar,
    [Popover.name]: Popover
  }
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
.xp{
  font-family: 'Bebas Neue', cursive;
}
</style>
