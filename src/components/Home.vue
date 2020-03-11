<template>
  <div>
    <el-button @click="outLogin">退出</el-button>
  </div>
</template>
<script>
export default {
  methods: {
    outLogin: function() {
      window.sessionStorage.clear();
      this.$router.push("/login");
    }
  }
};
</script>
<style lang="less" scoped>
</style>
