<template> <!-- TOP-MOST PART / NAVIGATION BAR -->
<!-- start desktop nav -->
  <nav class="hidden md:flex items-center justify-around py-[45px]">
      <div class="flex items-center">
          <img src="/profil.png" alt="profil" width="55">
          <p class="font-title text-xl ml-3 font-semibold text-white" >HiveMed</p>
      </div>

      <div class="font-dmsans text-white">
          <a href="#overview" class="mx-4">Overview</a>
          <a href="#hiw" class="mx-4">How It Works</a>
          <a href="#features" class="mx-4">Features</a>
          <a href="#benefits" class="mx-4">Benefits</a>
      </div>

      <div>
          <button class="font-dmsans text-white mr-6">Register</button>
          <button class="py-2 px-4 rounded-full bg-white font-dmsans">Login</button>
      </div>
  </nav>
  <!-- end desktop nav -->

  <!-- start mobile nav -->
<nav class="flex justify-between px-7 py-5 items-center md:hidden">
    <img src="/profil.png" width="43" alt="">
    <img src="/white-hamburger.png" width="37" alt="">
</nav>

</template>

<script>
export default {
    

}
</script>