<template>
  <div>
    <h1 class="about-title">About 1410-3</h1>
    <div class="about">
      <h3 class="about-content">Birthday:</h3>
      <h3 class="about-content">1989-10-11</h3>
      <h3 class="about-content">Living:</h3>
      <h3 class="about-content">Hiroshima or Kanagawa</h3>
      <h3 class="about-content">Important:</h3>
      <h3 class="about-content">Psychological Safety and Simplicity</h3>
      <h3 class="about-content">Favorite Lang:</h3>
      <h3 class="about-content">Ruby</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutPage",
};
</script>

<style scoped>
.about {
  display: grid;
  grid-template-rows: 1fr 1fr;
  grid-template-columns: 1fr 1fr;
  border: solid;
  border-color: rgb(245, 245, 245);
}

.about-content {
  height: 5rem;
  text-align: center;
  color: rgb(245, 245, 245);
}

.about-title {
  color: rgb(245, 245, 245);
}
</style>
