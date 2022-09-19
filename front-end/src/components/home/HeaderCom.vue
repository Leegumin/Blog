<template>
  <!-- Header-->
  <header id="Hello" class = "d-flex align-items-center">
    <div class = "container px-4 px-lg-5 text-center">
    </div>
  </header>
</template>

<script>
export default {
  name: 'HeaderCom',
}
</script>

<style scoped>
#Hello {
  background: linear-gradient(90deg, rgba(255, 255, 255, 0.3) 0%, rgba(255, 255, 255, 0.2) 100%), url("@/assets/img/hd-wallpaper-1867616_1920.jpg");
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 25vh;
}
</style>