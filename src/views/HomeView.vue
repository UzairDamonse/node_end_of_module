<template>
  <div id="home">
      <div class="homeLanding">
        <img src="https://picsum.photos/200" alt="">
        <img src="https://picsum.photos/200" alt="">
        <img src="https://picsum.photos/200" alt="">
      </div>
      <div id="homeLanding2">
        <div class="topHalf">
          <h2>FILL</h2>
          <h2>UP</h2>
          <h2>YOUR</h2>
          <h2>TANK</h2>
        </div>
        <div class="bottomHalf">
          <h2>EARN</h2>
          <h2>AND</h2>
          <h2>PAY</h2>
          <h2>LATER</h2>
        </div>
      </div>
    
  </div>
</template>

<script>
// @ is an alias to /src

export default {};
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#home {
  background-color: rgb(186, 214, 216);
  height: 100vh;
  overflow: hidden !important;
  position: relative;
}


.homeLanding {
  width: 100%;
  height: 250px;
  background-color: transparent;
  border: 1px solid rgb(255, 255, 255);
  position: absolute;
  top: 300px;
  transform: skew(0deg, -22.5deg);
  box-shadow: 29px 29px 58px #58747e, -29px -29px 58px #a3a7ae;
}

.homeLanding img{
  border-radius: 100%;
  aspect-ratio: 1;
  margin-top: 20px;
  transform: skew(0deg, 20deg);
  transform: translate()
}

#homeLanding2{
  display: block;
}

.topHalf{
  position: absolute;
  top: 0%;
  left: 10%;
  margin-bottom: 350px;
  font-size: 40px;
  text-align: left;
  margin-left: 20px;
}

.bottomHalf{
  position: absolute;
  bottom: 0%;
  left: 80%;
  font-size: 40px;
  text-align: left;
}

.topHalf h2{
  color: white;
  text-shadow: -1px -1px 0 rgb(0, 0, 0), 1px -1px 0 rgb(0, 0, 0), -1px 1px 0 rgb(0, 0, 0), 1px 1px 0 rgb(0, 0, 0);
}
.bottomHalf h2{
  color: white;
  text-shadow: -1px -1px 0 rgb(0, 0, 0), 1px -1px 0 rgb(0, 0, 0), -1px 1px 0 rgb(0, 0, 0), 1px 1px 0 rgb(0, 0, 0);
}




</style>
