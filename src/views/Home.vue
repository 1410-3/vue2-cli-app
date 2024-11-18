<template>
  <div class="home-page">
    <!-- <div>
      <img src="../assets/picture.png" alt="写真" />
    </div> -->
    <div>
      <p class="font-family">
        VueCLIでポートフォリオを作成しました。 <br />
        ごゆっくりどうぞ。
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomePage",
};
</script>

<style scoped>
.home {
  display: grid;
  grid-template-rows: 1fr;
  grid-template-columns: 1fr 1fr;
  border: solid;
  border-color: rgb(245, 245, 245);
}

.home div {
  display: flex;
  align-items: center;
  justify-content: center;
  color: rgb(245, 245, 245);
}

.font-family {
  font-family: "メイリオ", "Meiryo", sans-serif;
}
</style>
