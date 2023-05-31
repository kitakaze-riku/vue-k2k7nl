<template>
  <div class="l-first">
    <h2>
      {{ msg }}
    </h2>
    <div class="music-box">
      <iframe
        style="border-radius: 12px"
        src="https://open.spotify.com/embed/album/4uG8q3GPuWHQlRbswMIRS6?utm_source=generator"
        width="100%"
        height="352"
        frameBorder="0"
        allowfullscreen=""
        allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
        loading="lazy"
      ></iframe>
    </div>
  </div>
</template>

<script>
export default {
  name: 'l-first',
  props: {
    msg: String,
  },
};
</script>
<!-- Installed CLI Plugins -->
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.l-first {
  background: lightgray;
}
.music-box {
  color: white;
  padding: 16px;
  box-sizing: border-box;
}
</style>
