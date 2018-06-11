<template>
  <!-- <nav class="navbar navbar-default">
        <div class="navbar-header">
            <a href="#" class="navbar-brand">Stock App</a>
        </div>
        <div class="nav navbar-nav">
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </div>
    </nav> -->
  <nav class="navbar navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand"
         href="#">Stock Trader</a>
      <ul class="nav navbar-nav">
        <li class="nav-item">
          <router-link to='/portfolio'>
            <a class="nav-link">Portfolio</a>
          </router-link>
        </li>
        <li class="nav-item">
          <router-link to='/stocks'>
            <a class="nav-link">Stocks</a>
          </router-link>
        </li>
      </ul>
      <ul class="nav navbar-nav navbar-right">
        <li class="nav-item">
          <a class="nav-link"
             href="#">End Day</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle"
             href="#"
             id="navbarDropdown"
             role="button"
             data-toggle="dropdown"
             aria-haspopup="true"
             aria-expanded="false">
            Save & Load
          </a>
          <div class="dropdown-menu"
               aria-labelledby="navbarDropdown">
            <a class="dropdown-item"
               href="#">Save Data</a>
            <a class="dropdown-item"
               href="#">Load Data</a>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled"
             href="#">Funds: DYNAMIC</a>
        </li>
      </ul>
    </div>
  </nav>
</template>


<script>
export default {};
</script>



<style>

</style>
