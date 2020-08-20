<template>
  <div>
    <encabezado />
    <contenido />
    <pieDePagina />
  </div>
</template>

<script>
import encabezado from "./components/encabezado";
import contenido from "./components/contenido";
import pieDePagina from "./components/pieDePagina";

export default {
  name: "App",
  components: {
    encabezado,
    contenido,
    pieDePagina
  }
};
</script>

<style>
</style>
