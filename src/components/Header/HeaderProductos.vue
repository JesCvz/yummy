<template>
  <div class="container">
    <br />
    <h1 class="Titulo">Productos Disponibles</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      hover: false
    };
  }
};
</script>

<style scoped>
.Titulo {
  margin-top: 120px;
  margin-bottom: 200px;
}
h1 {
  text-align: center;
  font-weight: 700;
  font-size: 3.7em;
  color: #fff4f4;
  text-shadow: 0 4px 4px rgba(1, 1, 1, 0.76);
}
</style>