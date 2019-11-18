<template>
  <div id="app">
    <Logo color="green--outline" :width="150" :strokeWidth="10"/>
    <Logo color="red" :width="150" :strokeWidth="20"/>
  </div>
</template>

<script>
import Logo from './components/Logo'

export default {
  name: 'App',
  components: {
    Logo
  }
}
</script>
