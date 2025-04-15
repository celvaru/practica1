<template>
  <nav class="navbar navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand">Mi Negocio</a>
      <ul class="nav justify-content-end">
        <li class="nav-item">
          <b-nav-item class="nav-link text-dark" to="/">Inicio</b-nav-item>
        </li>
        <li class="nav-item">
          <b-nav-item class="nav-link text-secondary" to="/services">Servicios</b-nav-item>
        </li>
        <li class="nav-item">
          <b-nav-item class="nav-link text-secondary" to="/galery">Galería</b-nav-item>
        </li>
        <li class="nav-item">
          <b-nav-item class="nav-link text-secondary" to="/contact">Contacto</b-nav-item>
        </li>
      </ul>
    </div>
  </nav>
  
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>

</style>
