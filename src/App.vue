<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
@font-face {
  font-family: "Airbnb";
  src: url("../src/assets/font/AirbnbCereal-Medium.ttf") format("truetype");
}
*{
  margin: 0;
  padding: 0;
}
html {
  scroll-behavior: smooth;
}
body {
  font-family: Airbnb;
}
</style>
