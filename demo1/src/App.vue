<template>
  <div id="app">
    <Display></Display>
    <Increment></Increment>
  </div>
</template>

<script>
import Display from './components/Display.vue'
import Increment from './components/Increment.vue'
import store from './vuex/store'

export default {
  components: {
    Display: Display,
    Increment: Increment,
  },
  store: store // 在根组件加入 store，让它的子组件和 store 链接
}
</script>