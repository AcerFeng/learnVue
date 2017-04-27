<template>
  <div>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  data() {
    return {
      totalcount: 200,
      content: '',
    };
  },
  computed: {
    reduceCount() {
      return this.totalcount - this.content.length;
    },
  },
};
</script>

<style lang="less">

</style>
