<template>
  <div class="page">
    <p>
      Oops, không thể tìm thấy trang. Trở về
      <router-link to="/">trang chủ.</router-link>
    </p>
  </div>
</template>

<script>
export default {
  name: "NotFound",
};
</script>

<style scoped>
.page {
  text-align: center;
  margin-top: 100px;
  font-size: 18px;
}
</style>
