<template>
  <div class="header-background">
    <div class="header-text">
      <h1>William Skaggs</h1>
      <h1>Portfolio</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String
  }
}

</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inconsolata&display=swap');
.header-background {
  background: #2c3e50;
  width: 100%;
  height: 100px;
}

.header-text {
  color: white;
  font-family: 'Inconsolata', monospace;
  height: max-content;
  margin-left: 20%;
  margin-right: 20%;
  text-align: left;
}

h1 {
  font-weight: normal;
}

</style>