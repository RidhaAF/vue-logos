<template>
  <div class="logos-wrapper">
    <h2 class="title-header">Find Best Logo</h2>
    <div class="item-logos">
      <img src="../assets/facebook.png" alt="Facebook" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/instagram.png" alt="Instagram" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/line.png" alt="Line" class="logo" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Logos",
};
</script>

<style scoped>
.title-header {
  color: #41b883;
  margin-bottom: 80px;
}

.logos-wrapper {
  width: 70%;
  overflow: hidden;
  margin: auto;
}

.item-logos {
  float: left;
  margin-right: 20px;
  margin-bottom: 20px;
  width: 150px;
  height: 150px;
}

.item-logos .logo {
  width: 150px;
  height: 150px;
}
</style>
