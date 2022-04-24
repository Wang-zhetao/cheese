<template>
  <div class="nav-wrapper">
    <div class="content">
      标签页面
    </div>
    <Nav/>
  </div>
</template>

<script lang="ts">
</script>

<style lang="scss" scoped>
.nav-wrapper{
  border: 1px solid green;
  display: flex;
  flex-direction: column;
  height: 100vh;
}
.content{
  border: 1px solid blue;
  flex-grow: 1;
  overflow: auto;
}
</style>