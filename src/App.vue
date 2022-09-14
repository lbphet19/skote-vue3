<script setup>

import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/partials/Header.vue";
import SideBar from "./components/partials/SideBar.vue";



</script>

<template>
  <Header />
  <SideBar />
  <div class="main-content">
    <div class="page-content">
      <div class="container-fluid">
        <RouterView/>
      </div>
    </div>
  </div>
</template>

