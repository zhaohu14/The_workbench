<template>
  <div class="index">
    <div class="Data_Tracking"></div>
    <div></div>
    <div></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.index {
  width: 1800px;
  height: 1000px;
  margin: 0 auto;
  position: relative;
  border: 1px solid black;
}
.Data_Tracking {
  width: 720px;
  height: 282px;
  position: absolute;
  left:17px;
  top: 32px;
  border: 1px solid black;
}
</style>
