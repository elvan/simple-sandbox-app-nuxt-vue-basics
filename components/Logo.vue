<template>
  <div class="VueToNuxtLogo">
    <div class="Triangle Triangle--two"></div>
    <div class="Triangle Triangle--one"></div>
    <div class="Triangle Triangle--three"></div>
    <div class="Triangle Triangle--four"></div>
  </div>
</template>

<style>
.VueToNuxtLogo {
  display: inline-block;
  position: relative;
  width: 245px;
  height: 180px;
  overflow: hidden;
  animation: turn 2s linear forwards 1s;
  transform: rotateX(180deg);
}
.Triangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 0;
  height: 0;
}
.Triangle--one {
  border-right: 105px solid transparent;
  border-bottom: 180px solid #41b883;
  border-left: 105px solid transparent;
}
.Triangle--two {
  top: 30px;
  left: 35px;
  border-right: 87.5px solid transparent;
  border-bottom: 150px solid #3b8070;
  border-left: 87.5px solid transparent;
  animation: goright 0.5s linear forwards 3.5s;
}
.Triangle--three {
  top: 60px;
  left: 35px;
  border-right: 70px solid transparent;
  border-bottom: 120px solid #35495e;
  border-left: 70px solid transparent;
  animation: goright 0.5s linear forwards 3.5s;
}
.Triangle--four {
  top: 120px;
  left: 70px;
  border-right: 35px solid transparent;
  border-bottom: 60px solid #fff;
  border-left: 35px solid transparent;
  animation: godown 0.5s linear forwards 3s;
}

@keyframes turn {
  100% {
    transform: rotateX(0deg);
  }
}
@keyframes godown {
  100% {
    top: 180px;
  }
}
@keyframes goright {
  100% {
    left: 70px;
  }
}
</style>
