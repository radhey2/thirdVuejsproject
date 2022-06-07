<template>
 <div id="app">
  <h3>What is your favorite kind of taco?</h3>
  <textarea v-model="tacos"></textarea>
  <br>
  <button v-show="tacos" type="submit">Let us know!</button>
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  data() {
    return {
      tacos: ''
    }
  }
}
</script>
