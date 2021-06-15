<template>
  <div class="home">
    <input type="number">
    <button @click="result()">住所自動入力</button>
    <p>住所：{{ adress }}</p>
  </div>
</template>

<script>
export default {
  methods: {
    result() {
      this.$router.push({ name: "Detail", params:{} })
    }
  }
};
</script>

<style scoped>
.home {
  align-items: left;
}
</style>