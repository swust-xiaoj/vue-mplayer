<template>
  <div class="hello">
    <mt-swipe :auto="2000" class='swiper'>
      <mt-swipe-item class="slide1">1</mt-swipe-item>
      <mt-swipe-item class="slide2">2</mt-swipe-item>
      <mt-swipe-item class="slide3">3</mt-swipe-item>
    </mt-swipe>
  </div>
</template>

<script>
export default {
    name: 'HelloWorld',
    data() {
        return {
            msg: 'Welcome to Your Vue.js App'
        };
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.swiper {
    height: 200px;
    font-size: 20px;
}
.slide1 {
    background-color: #0089dc;
    color: #fff;
    line-height: 200px;
    height: 200px;
}
.slide2 {
    background-color: #ffd705;
    color: #fff;
    line-height: 200px;
    height: 200px;
}
.slide3 {
    background-color: #ff2d4b;
    color: #fff;
    line-height: 200px;
    height: 200px;
}
</style>
