<template>
  <div class="container">
    <ul class="menu">
      <li><router-link to="/">Berita Otomotif</router-link></li>
      <li><router-link to="/about">Berita lalu lintas</router-link></li>
      <li><router-link to="/contact">Berita Iklim cuaca</router-link></li>
    </ul>
    <h1>Halo, Selamat datang di <span id="syal-news">Syal News</span>. Portal berita masa kini.</h1>
  </div>
</template>

<style scoped>
  .container {
    width: 100%;
    margin: 100px auto;
    text-align: center;
  }
  .menu {
    list-style: none;
    margin-bottom: 20px;
  }
  .menu li {
    display: inline;
  }
  .menu li a {
    color: #333;
    padding: 20px;
    text-decoration: none;
  }
  .menu li a:hover {
    background-color: #333;
    color: #eaeaea;
  }
</style>