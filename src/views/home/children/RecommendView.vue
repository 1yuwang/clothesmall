<template>
  <div class="recommend">
    <div v-for="(item, index) in recommends" :key="index" class="recommend-item">
      <a :href="item.link">
        <img :src="item.image" alt="">
        <div class="aaa">{{item.title}}</div>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    recommends: {
      type: Array,
      default() {
        return []
      }
    }
  }

}
</script>

<style>
  .recommend {
    display: flex;
    width: 100%;
    text-align: center;
    padding:10px 0 30px 0;
    border-bottom: 8px solid #eee;
  }

  .recommend-item {
    flex: 25%;
  }

  .recommend-item img {
    width: 90%;
    margin-bottom: 5px;
  }

</style>