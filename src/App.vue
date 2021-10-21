<template>
  <div id="app">
    <Headers/>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld/>
    <Form/>
    <Footer/>

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Headers from './components/Header.vue'
import Footer from './components/Footer.vue'
import Form from './components/FormComponent.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Headers,
    Footer,
    Form
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
