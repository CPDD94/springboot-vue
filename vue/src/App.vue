<template>
  <div id="app">
    <Header></Header>
    <div style="display: flex">
      <Aside></Aside>
      <Home></Home>
    </div>
  </div>
</template>

<script>

import Header from "./components/Header";
import Aside from "./components/Aside";
import Home from "./views/Home";

export default {
  name: 'app',
  components: {
    Header,
    Aside,
    Home
  }
}
</script>

<style>

</style>
