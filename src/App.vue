<template>
  <div id="app">
    <mt-header fixed :title="hconf.title">
      <router-link to='/' slot="left">
        <mt-button icon='back'></mt-button>
      </router-link>
      <mt-button icon='more' slot="right"></mt-button>
    </mt-header>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      hconf: {
        show: true,
        title: 'home',
      }
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 40px;
}
</style>
