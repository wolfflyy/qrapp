<template>
  <qrapp/>
</template>

<script>
import QrStream from './components/QrStream.vue'

export default {
  name: 'App',
  components: {
    qrapp:QrStream
  }
}
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
.mb {
  margin-bottom: 10px;
}
.center {
  display: flex;
  align-items: center;
  justify-content: center;
}
.result {
  width: 100%;
  text-align: left;
}
</style>
