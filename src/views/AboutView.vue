<template>
  <div id="about">
    <h1>This is an about page</h1>
    <div class="aboutDetails">

    </div>
  </div>
</template>

<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#about{
  background-image: url(../assets/map.jpg);
  background-size: cover;
  height: 100vh;
}

.aboutDetails{
  background-color: white;
  width: 100%;
  height: 400px;
  transform: skew(0deg, -30deg);
}
</style>
