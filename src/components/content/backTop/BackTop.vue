<template>
  <div class="back-top" @click="backClick">
    <a href="#">
    <img src="~assets/img/common/top.png" alt="">

    </a>
  </div>
</template>

<script>
  export default {
    methods: {
      backClick() {
        this.$emit('backClick')
      }
    }
  }
</script>

<style>
  .back-top {
    position: fixed;
    right: -30px;
    bottom: 44px;
  }
  .back-top img {
    width: 60%;
  }
</style>