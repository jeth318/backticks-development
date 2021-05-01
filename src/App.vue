<template>
  <div class="main-wrapper">
    <div class="brand-wrapper">
      <img alt="Backticks Development logo" src="./assets/backticks-development_brand.png">
    </div>
    <div class="animation-wrapper">
      <img class="animation-img" alt="Coding hands" src="./assets/coding-hands.gif">
    </div>
    <div class="attribution-wrapper">
      <a href="https://cliply.co">Animation art by cliply.co</a>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>

html {
  height: 100vh;
  background: linear-gradient(180deg, white, #d8d8d8);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 50px;
}

img {
  max-width:100%;
  height:auto;
}

.animation-img {
  border-radius: 10%;
}

.main-wrapper {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.animation-wrapper {
  margin-top: 90px;
}

.attribution-wrapper {
  padding-right: 10px;
  position: absolute;
  bottom: 0;
  right: 0;
}

</style>
