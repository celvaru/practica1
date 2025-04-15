<template>
  <div id="app">
    <nav class="navbar navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand">Mi Negocio</a>
      <ul class="nav justify-content-end">
        <li class="nav-item">
          <b-nav-item to="/" exact active-class="active" class="mx-2">Inicio</b-nav-item>
        </li>
        <li class="nav-item">
          <b-nav-item to="/services" exact active-class="active" class="mx-2">Servicios</b-nav-item>
        </li>
        <li class="nav-item">
          <b-nav-item to="/galery" exact active-class="active" class="mx-2">Galería</b-nav-item>
        </li>
        <li class="nav-item">
          <b-nav-item to="/contact" exact active-class="active" class="mx-2">Contacto</b-nav-item>
        </li>
      </ul>
    </div>
  </nav>
  <div class="container mt-4">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>

</style>
