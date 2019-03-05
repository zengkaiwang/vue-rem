<template>
  <!-- 设计稿是640px，有一个红色盒子宽高都是320px，里面的文字是28px，那么下面是这个例子的代码 -->
  <div class="index-page">
      <span class="title">我是标题</span>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .index-page {
    width: 3.2rem;
    height: 3.2rem;
    background: red
  }
  .title {
    font-size: .28rem;
  }
</style>
