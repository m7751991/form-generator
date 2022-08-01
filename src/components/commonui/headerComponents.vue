<template>
  <div class="fd-xt-header">
    {{ text }}
  </div>
</template>
<script>
export default {
  props: {
    text: {
      type: String,
      default: "头部数据",
    },
    name:''
  },
  created(){
    console.log(this.$props,'texttext');
  }
};
</script>

<style lang="less" scoped>
.fd-xt-header {
  border: 1px solid rgb(75, 165, 255);
  box-shadow: 1px 2px 1px 1px;
  border-radius: 5px;
}
</style>