<template>
  <div class="l-second">
    <h2>
      {{ msg }}
    </h2>
    <ul class="hobby-lists">
      <li>sanpo</li>
      <li>sauna</li>
      <li>Watching the English Premier League.</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'l-second',
  props: {
    msg: String,
  },
};
</script>
<!-- Installed CLI Plugins -->
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.l-second {
  background: pink;
  border-radius: 10px;
}
p {
  color: white;
}
.hobby-lists {
  display: flex;
  flex-direction: column;
}

.hobby-lists li {
  border: none;
}

.hobby-lists li:before {
  content: '・';
}
</style>
