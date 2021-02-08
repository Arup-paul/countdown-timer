<template>

  <Counter
    :year="2021"
    :month="1"
    :date="9"
    :hour="11"
    :minute="2"
    :second="59"
    :millisecond="2"

  />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Counter from './components/Counter.vue';

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>