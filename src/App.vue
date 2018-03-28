<template>
    <div id="app">
      <div id="main" class="has-text-centered">
        <h1 class="title is-1">VUE PARTICLES IS ASESOME</h1>
        <a href="https://bulma.io" target="_blank">
          <img src="https://bulma.io/images/made-with-bulma.png" alt="Made with Bulma" width="128" height="24">
        </a>
      </div>
      <vue-particles
        color="#dedede"
        :particleOpacity="0.7"
        :particlesNumber="80"
        shapeType="circle"
        :particleSize="4"
        linesColor="#dedede"
        :linesWidth="1"
        :lineLinked="true"
        :lineOpacity="0.4"
        :linesDistance="150"
        :moveSpeed="3"
        :hoverEffect="true"
        hoverMode="grab"
        :clickEffect="true"
        clickMode="push"
      >
      </vue-particles>
    </div>
 </template>

<script>
export default {
  name: 'App'
}
</script>

<style>
html, body, #app {
    height: 100%;
}

#app {
  position: relative;
  background-image: url('./assets/image/bgimage.jpeg');
  background-size: cover;
}

#main {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translateY(-50%) translateX(-50%);
}

h1 {
  color: #fdebeb !important;
  text-shadow: 5px 5px 0px #000000;
  font-family: 'Dosis', sans-serif;
}
</style>
