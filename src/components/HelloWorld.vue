<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="message">message</div>
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
<style scoped lang="scss">
h1{
  width: 750px;
  height: 750px;
  background: #f00;
  box-sizing: border-box;
  display:grid;
}
.message{
  display: flex;
}
::placeholder {
  color: gray;
}

</style>
