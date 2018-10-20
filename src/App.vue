<template>
  <div id="app">
    <CatsFood/>
  </div>
</template>

<script>
import CatsFood from './components/CatsFood.vue'

export default {
  name: 'app',
  components: {
    CatsFood
  }
}
</script>

<style>

html, body {
  width: 100%;
  height: 100%;
  overflow: hidden;
}

body {
    background:url("./assets/Shadow.png") no-repeat,
                url("./assets/Pattern.png") no-repeat;
    background-position: center center;
    background-size: cover;
    background-attachment: fixed;
}

#app {

}


</style>
