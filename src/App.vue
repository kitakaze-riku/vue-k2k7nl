<template>
  <div id="app">
    <div></div>
    <Navigation navmsg="navigation" />
    <HelloWorld msg="I'm going to start learning Vue.js！！！！" />
  </div>

  <section>
    <h2>2カラムレイアウト</h2>
    <div class="flex">
      <Layoutfirst
        class="f-box1"
        msg="My favorite artist is Green Day."
      ></Layoutfirst>
      <Layoutsecond class="f-box2" msg="My hobbies."></Layoutsecond>
    </div>
  </section>
  <!-- <img alt="Vue logo" src="https://vuejs.org/images/logo.png" /> -->
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Navigation from './components/nav.vue';
import Layoutfirst from './components/Layout_first.vue';
import Layoutsecond from './components/Layout_second.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navigation,
    Layoutfirst,
    Layoutsecond,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.flex {
  display: flex;
  gap: 16px;
}

.f-box1 {
  flex-basis: 50%;
}
.f-box2 {
  flex-basis: 50%;
}
</style>
