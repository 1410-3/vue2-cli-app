<template>
  <div class="footer my-footer-color">
    <div class="font-color">&copy; {{ new Date().getFullYear() }}</div>
  </div>
</template>

<script>
export default {
  name: "my-footer",
};
</script>
<style scoped>
.my-footer-color {
  background: linear-gradient(rgb(240, 128, 255), rgb(128, 160, 255));
}
.font-color {
  color: rgb(245, 245, 245);
}
</style>
