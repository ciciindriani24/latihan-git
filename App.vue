<template>
  <div>
    <Navbar></Navbar>
    <br>
    <br>
    <AvatarComponent></AvatarComponent>
    <br>
    <br>
    <center><strong> <font size="5">- MY SKILL -</font></strong><br></center>
    <br>
    <br>
    <CardComponent2></CardComponent2>
    <br>
    <br>
    <center><strong> <font size="5">- RIWAYAT PENDIDIKAN -</font></strong><br></center>
    <br>
    <CardComponent></CardComponent>
    <br>
    <br>
    <br>
    <center><strong> <font size="5">- GALLERY -</font></strong><br></center>
    <br>
    <GalleryComponent></GalleryComponent>
    <br>
    <br>
    <Footer></Footer>
  </div>
</template>
<script setup>
 import Navbar from './components/Navbar.vue';
 import AvatarComponent from './components/AvatarComponent.vue';
 import CardComponent2 from './components/CardComponent2.vue';
 import CardComponent from './components/CardComponent.vue';
 import GalleryComponent from './components/GalleryComponent.vue'
 import Footer from './components/Footer.vue';
</script>