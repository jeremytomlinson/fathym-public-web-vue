<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <div id="header">
      <img src="./assets/pimpire_logo.png" alt="PIMPIRE" />
  </div>
  <HelloWorld msg="Vue.js + TypeScript App" />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "./components/HelloWorld.vue";

@Options({
  components: {
    HelloWorld,
  },
})
export default class App extends Vue {}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin:0px auto;
  min-height:100%;
}

#header 
{
	margin:0;
	text-align: center;
	padding:10px 0px 10px 0px;
}

    #header img 
    {
        max-width: 100%;
        height: auto;
    }
</style>
