<template>
  <nav class="navbar navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand">Mi Negocio</a>
      <ul class="nav justify-content-end">
        <li class="nav-item">
          <a class="nav-link active text-dark" aria-current="page" href="#">Inicio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-secondary" href="#">Servicios</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-secondary" href="#">Galería</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-secondary" href="#">Contacto</a>
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
