<template>
  <div class="hello">
    <text class="h1">{{ msg }}</text>
    <text class="h2">Essential Links</text>
    <text>数字健康APP</text>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Weex App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  align-items: center;
  width: 750px;
  margin-top: 12px;
}
.h1, .h2 {
  font-weight: normal;
}
.h1 {
  font-size: 32px;
  margin: 14px;
}
.h2 {
  font-size: 26px;
  margin: 10px;
}
.ul {
  flex-direction: row;
  padding: 0;
}
.li {
  margin: 0 10px;
}
.link-label {
  font-size: 18px;
  color: #00BDFF;
}
</style>
