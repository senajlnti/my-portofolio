<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Flowbite logo" image-url="https://th.bing.com/th/id/OIP.D5Bmc2SVsk7fAnImJVPZRQHaHa?pid=ImgDet&rs=1">
          SENA JULIANTI
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Home</NavbarLink>
          <NavbarLink link="#">About</NavbarLink>
          <NavbarLink link="#">Gallery</NavbarLink>
          <NavbarLink link="#">Contact</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
    <div class="px-4 mx-auto max-w-screen-xl text-center py-5 lg:py-5">
    <img src="src/assets/halo.png">
    </div><br>
    
<section class="bg-white dark:bg-dark-900">
    <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16 grid lg:grid-cols-2 gap-8 lg:gap-16">
        <div class="flex flex-col justify-center">
            <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-dark-900 md:text-5xl lg:text-6xl dark:text-white">PROFIL</h1>
            <p class="mb-8 text-lg font-normal text-dark-500 lg:text-xl dark:text-dark-400">Haii nama saya Sena Julianti, seorang pelajar yang menyukai Desain, saya seorang siswa dari SMK ASSALAAM BANDUNG.
                Saya selalu ingin mempelajari hal-hal baru yang menarik buat saya.
            </p>          
        </div>
        <div>
            <img class="mx-auto w-full lg:max-w-xl h-60 rounded-lg sm:h-96 shadow-xl" src="src/assets/sena.png"  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
        </div>
    </div>
</section>
<div class="px-4 mx-auto max-w-screen-xl text-center py-5 lg:py-5">
    <img src="src/assets/datadiri.png">
    </div><br>


</template>
