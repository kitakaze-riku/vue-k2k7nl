<template>
  <div class="nav-color">
    <h2>{{ navmsg }}</h2>
    <nav>
      <ul>
        <li><a href="">home</a></li>
        <li><a href="">about</a></li>
        <li><a href="">profile</a></li>
      </ul>
    </nav>
    <p>単一ファイルとは？</p>
    <a href="https://qiita.com/notch0314/items/e9f2b704a340824393b8"
      >export defaultってなにそれ美味しいの？</a
    >
  </div>
</template>

<script>
export default {
  name: 'Navigation',
  props: {
    navmsg: String,
  },
};
</script>
<!-- Installed CLI Plugins -->
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-color {
  padding: 10px 0;
  background-color: lightgreen;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
  border-bottom: 1px solid;
}
a {
  color: black;
}
</style>
