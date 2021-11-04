<template>
  <div class="home">
    <Two msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Two from '@/components/Two.vue'

export default {
  name: 'Home',
  components: {
    Two
  }
}
</script>
