<template>
  <div class="about">
    
  </div>
</template>

<script>

export default {
  name: "about",
  data () {
    return {
      speed: 100
    }
  },
  mounted () {
    // this.back();
  },
  methods: {



  }
}
</script>

<style scoped>
body,
html {
  margin: 0;
  padding: 0;
  height: 100%;
}

svg {
  display: block;
  width: 100%;
  height: 100vh;
  position: fixed;
  top: 0;
  left: 0;
}

.scrollElement {
  position: absolute;
  height: 6000px;
  width: 100px;
  top: 0;
  z-index: 0;
}
</style>