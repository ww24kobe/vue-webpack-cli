<template>
  <div>
    App根组件-{{ msg }}
    <loginCom></loginCom>
  </div>
  
</template>

<script>
import loginCom from "@/components/login.vue";
export default {
  data() {
    return {
      msg: "app-data",
    };
  },
  components: {
    loginCom,
  },
};
</script>

<style scoped>
  div {
    width: 500px;
    height: 500px;
    border: 2px solid #ccc;
    text-align: center;
  }
</style>