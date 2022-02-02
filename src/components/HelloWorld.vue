<template>
  <div>
    <v-zoomer id="zoomer">
      <img id="map" src="../media/image.png">
    </v-zoomer>
  </div>
</template>

<script>
import Vue from "vue";
import VueZoomer from "vue-zoomer";

Vue.use(VueZoomer);

export default {
  name: "HelloWorld",
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#zoomer {
  width: 99% vw;
  height: 99% vh;
  border: solid 1px silver;
}
#map {
  margin: 10px;
  padding: 10px;
  object-fit: contain;
  width: 100%;
  height: 100%;
}
</style>
