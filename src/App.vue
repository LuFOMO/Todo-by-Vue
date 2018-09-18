<template>
  <div id="app" class="app">
    <h1>{{msg}}</h1>
    <router-view/>
  </div>
</template>

<script>
import './assets/styles/todo.css'
export default {
  name: 'App',
  data () {
    return {
      msg: '123s'
    }
  }
}
</script>

<style>

</style>
