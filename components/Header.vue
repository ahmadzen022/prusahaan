<template>
  <nav class="navbar navbar-expand-lg navbar-light  shadow-sm fixed-top">
    <div class="container">
      <img src="~/assets/logo.png" alt="logo">
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <NuxtLink class="nav-link active" aria-current="page" to="#">Home</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="#about">about</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="#product">Product</NuxtLink>
          </li>
          <!-- <li class="nav-item">
              <a class="nav-link" to="#">contact me</a>
            </li> -->
        </ul>
      </div>
    </div>
  </nav>
</template>

<style>
/* .navbar{
  padding-right: 30%;
} */
</style>