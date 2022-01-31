<template>
  <div>
    我是首页
    <hr />
    <button @click="go">前往 About 页面</button>
  </div>
</template>

<script>
export default {
  methods: {
    go() {
      this.$router.push("about");
    },
  },
};
</script>

<style lang="scss" scoped>
</style>