<template>
  <div id="app">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css"
      integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" crossorigin="anonymous">
    <HelloWorld/>
    <ContactInformation />
    <meta name="theme-color" content="#243b55"/>
    <!-- <img alt="Vue logo" src="./assets/128.jpg"> -->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ContactInformation from './components/ContactInformation.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    ContactInformation
  }
}
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #f3f3f3;
  margin-top: 60px;
}

img {
  width: 100%;
}

body {
  background-image: url('@/assets/128.jpg');
  background-position: top;
  background-position-y: 14%;
  background-blend-mode: screen;
}

@media only screen and (max-width: 400px) {
  body {
    background-image: url('@/assets/128.jpg');
    background-position-y: 9%;
    background-size: 150%;

  }
}
</style>
