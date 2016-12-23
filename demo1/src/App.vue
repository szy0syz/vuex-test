<template>
  <div id="app">
    <Display></Display>
    <Increment></Increment>
  </div>
</template>

<script>
import Display from './components/Display.vue'
import Increment from './components/Increment.vue'

export default {
  components: {
    Display: Display,
    Increment: Increment
  }
}
</script>