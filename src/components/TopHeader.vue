<template>
  <div id="header">
    <h1 id="logo" >MS</h1>
    <el-button>Contact</el-button>
  </div>
</template>

<script>
export default {
  name: 'TopHeader'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#header{
  display: flex;
  justify-content: space-around;
  align-items: center;
}

#contact-button{

}

</style>
