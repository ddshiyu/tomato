<script setup lang="ts">
</script>

<template>
  <main>
    <video autoplay muted loop>
      <source src="@/assets/video.mp4" type="video/mp4">
    </video>
  </main>
</template>

<style scoped>
main {
  width: 100vw;
  height: 100vh;
  overflow: hidden;
}
video {
  width: 100%;
  height: 100%;
  object-fit: fill;
}

</style>
