<template>
  <div class="test">
    <div class="wrapper"></div>
    <div class="wrapper-left"></div>
    <div class="wrapper-right"></div>
  </div>
</template>

<script>
export default {
  components: {}
};
</script>


<style lang="scss">
.test {
  min-height: 100vh;
  width: 100%;
}
.wrapper {
  min-height: 100vh;
  padding: 0 calc((1280px - 100vw) / 2);
}

.wrapper-left {
  min-height: 100vh;
  padding-left: calc((1280px - 100vw) / 2);
}
.wrapper-right {
  min-height: 100vh;
  padding-right: calc((1280px - 100vw) / 2);
}


.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
