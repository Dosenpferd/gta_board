<template>
  <div className="page__header">
    <img src="./assets/images/logo.svg" className="logo">
    <ul>
      <li>
        Dummy
      </li>
      <li class="ms-auto">
        Login
      </li>
    </ul>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
@import "./assets/scss/index.scss";
</style>
