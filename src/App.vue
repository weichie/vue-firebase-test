<template>
  <div id="app">
    <Header />
    <router-view></router-view>
  </div>
</template>

<script>
  import Header from './components/elements/Header'

  export default {
    name: 'app',
    components: {
      Header
    }
  }
</script>