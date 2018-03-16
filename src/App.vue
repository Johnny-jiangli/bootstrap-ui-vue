<template>
  <div>
   <Nav/>
    <div id="app">
      <b-container>
        <Cards/>
        <Table/>
      <!--<router-view/>-->
      </b-container>
    </div>
  </div>
</template>

<script>
import Cards from './components/Cards';
import Nav from './components/Nav';
import Table from './components/Table';

export default {
  name: 'App',
  components: {
    Cards,
    Nav,
    Table,
  },
};
</script>

<style lang="scss">
@import './assets/styles/custom-bootstrap.scss';
@import '../node_modules/bootstrap/scss/bootstrap.scss';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
