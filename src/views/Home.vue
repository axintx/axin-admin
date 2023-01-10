<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
// 1. VSCode 而言， 默认一个 tab 等于 4 个空格， 而 ESLint 希望一个 tab 为两个空格
// 2. ESlint 和 prettier 之间的冲突问题
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  created() {
    console.log('created')
  }
}
</script>
