<template>
  <div id="micomponente">
    <hr />
    <h1>Este es mi componente</h1>
    <h2>{{ subtitulo }}</h2>
  </div>
</template>

<script>
export default {
  name: "MiComponente",
  data() {
    return {
      subtitulo: "Soy el subtitulo del componente",
    };
  },
};
</script>
