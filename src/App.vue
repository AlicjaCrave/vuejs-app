<template>

  <img alt="Vue logo" src="./assets/logo.png">
      <div class="containter">
        <page-home/>
      </div>
</template>

<script>
import PageHome from './components/PageHome.vue'
export default {
  name: 'App',
  components: {
    PageHome,
  }
}
</script>

<style>
@import "assets/styles.css";
</style>
