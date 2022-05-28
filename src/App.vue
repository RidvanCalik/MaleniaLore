<script setup>
import MainVue from './Main.vue';
</script>

<template>
  <section class="a">
    <div class="title">
      <h1>Malenia Blade Of Miqulla</h1>
      <iframe scrolling="no" src="./program/index.html"></iframe>
    </div>
  </section>
  <section>
    <MainVue></MainVue>
  </section>
</template>

<style>
#app {
  scroll-snap-type: y mandatory;
  margin: 0 auto;
  height: 100vh;
  font-weight: normal;
  overflow-y: scroll;
}

#app::-webkit-scrollbar {
  display: none;
}

section {
  scroll-snap-align: start;
  height: 100vh;
  width: 100%;
  display: flex;
  justify-content: center;
}

.title {
  width: 100%;
  height: 100%;
  position: relative;
  display: flex;
}

.title h1 {
  letter-spacing: 0.5em;
  font-size: 2rem;
  color: white;
  z-index: 1000;
  text-align: center;
  transform: translate(-50%, -50%);
  left: 50%;
  top: 50%;
  position: absolute;
}

iframe {
  box-shadow: 10px 10px 8px 10px #080606;
  border: none;
  width: 100%;
  height: 100%;
}
</style>
