<template>
  <div id="app">
    <Header/>
    <router-view/>
  </div>
</template>

<script>
import "./App.css";
import Header from "./components/Header";

export default {
  components: {
    Header
  }
};
</script>