<template>
<!--  <HelloWorld msg="Welcome to Your Vue.js App"/>-->
  <WebShell msg="****************系统信息：正在连接容器****************" />
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import WebShell from "@/components/WebShell";

export default {
  name: 'App',
  components: {
    WebShell,
    // HelloWorld
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
</style>
