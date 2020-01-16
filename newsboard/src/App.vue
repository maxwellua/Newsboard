<template>
  <div id="app">
    <header-section class="header-bar"></header-section>
    <div><router-view/></div>
    <footer-section class="footer-bar"></footer-section>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 98vh;
  display: flex;
  flex-direction: column;
  justify-content: space-between;

}

.header-bar {
  height: 50px;
  width: 100%;
  background-color: darkslategrey;
}

.footer-bar {
  height: 50px;
  width: 100%;
  background-color: darkgoldenrod;
}

</style>
