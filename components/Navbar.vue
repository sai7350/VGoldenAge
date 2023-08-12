<template>
    <div>
        <div class="navbar border hover:shadow-md bg-base-100">
  <div class="navbar-start">
    <div class="dropdown">
      <label tabindex="0" class="btn btn-ghost lg:hidden">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /></svg>
      </label>
      <ul tabindex="0" class="menu menu-sm  dropdown-content mt-3 z-[1] p-2 shadow bg-base-100  w-52 ">
        <li class="hover:shadow-xl rounded-lg p-4 btn glass opacity-70"><a>Home</a></li>
        <li>
          <a>Parent</a>
          <ul class="p-2 ">
            <li><a>Submenu 1</a></li>
            <li><a>Submenu 2</a></li>
          </ul>
        </li>
        <li class=" hover:shadow-xl btn glass p-4  opacity-70"><a>About us</a></li>
      </ul>
    </div>
    <a class="text-2xl font-bold">
      vGoldenAge</a>
  </div>
  <div class="navbar-center hidden lg:flex">
    <ul class=" ml-56 menu-horizontal  px-1">
      <li class=" hover:shadow-xl p-4  btn glass opacity-70"><a>Home</a></li>
      <li tabindex="0">
        <details class="ml-8 hover:shadow-xl rounded-lg p-4 btn glass opacity-70" >
          <summary>Parent</summary>
          <ul class="p-2">
            <li><a>Submenu 1</a></li> 
            <li><a>Submenu 2</a></li>
          </ul>
        </details>
      </li>
      <li class="ml-6 hover:shadow-xl p-4 btn glass opacity-70 "><a>About us</a></li>
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