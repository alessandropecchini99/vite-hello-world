<script>

</script>



<template>
  <div class="backgroundImg"></div>

  <h1>La prima app Vite firmata Pek!</h1>
  <p>Figo!</p>
</template>



<style scoped>
h1 {
  color: rgb(6, 112, 0);
}

p {
  color: rgb(42, 92, 0);
}

.backgroundImg {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background-image: url(doodle.webp);
  opacity: 0.03;
  filter: invert();
  z-index: -1;
}
</style>