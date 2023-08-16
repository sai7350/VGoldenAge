<template>
    <div>
        <div class="navbar border hover:shadow-md bg-base-100">
  <div class="navbar-start">
    <div class="dropdown">
      <label tabindex="0" class="btn btn-ghost lg:hidden">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /></svg>
      </label>
      <ul tabindex="0" class="menu menu-sm  dropdown-content mt-3 z-[1] p-2 shadow bg-base-100  w-52 ">
        <li class="hover:shadow-xl rounded-lg p-4 btn glass opacity-70"><NuxtLink to="/">Home</NuxtLink></li>
        <li>
          <a href="/photos">Photos</a>
        </li>
        <li class=" hover:shadow-xl btn glass p-4  opacity-70"><NuxtLink to="/aboutUs">About us</NuxtLink></li>
      </ul>
    </div>
    <a class="text-2xl font-bold" href="/">
      vGoldenAge</a>
  </div>
  <div class="navbar-center hidden lg:flex">
    <ul class=" ml-56 menu-horizontal  px-1">
      <li class=" hover:shadow-xl p-4  btn glass opacity-70"><NuxtLink to="/">Home</NuxtLink></li>
     
      <li class=" hover:shadow-xl p-4  btn glass opacity-70 ml-7">
          <NuxtLink to="/photos">Photos</NuxtLink>
        </li>
     
      <li class="ml-6 hover:shadow-xl p-4 btn glass opacity-70  "><NuxtLink to="/aboutUs">About us</NuxtLink></li>

      <!-- <li class="ml-6 "><NuxtLink to="/contactUs"
               class="inline-flex text-white bg-indigo-500 border-0 px-2 mt-1 py-1  glass focus:outline-none hover:bg-indigo-700 rounded text-lg"
            >
              CONTACT US
            </NuxtLink></li> -->
    </ul>
  </div>
 
</div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>