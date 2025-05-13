<template>
<div class="home">
    <div>
       <img class="robot" src="../assets/robot-home.png" alt="">
    </div>
    <div>
      <router-link to="/build">НАЧНИ</router-link> собирать робота
    </div>
</div>
</template>

<script setup>

</script>

<style scoped>
  .home{
    text-align: center;
  }
  .robot{
    height: 300px;
  }
</style>
