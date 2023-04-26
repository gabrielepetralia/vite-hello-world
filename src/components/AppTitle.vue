  <script>
    export default {
      name : "AppTitle",
      data () {
        return {
          title : "La mia prima app con Vite!"
        }
      }
    }
  </script>

<template>
  <h1>{{ title }}</h1>
</template>

<style scoped>
  h1 {
    text-align: center;
    margin : 50px 0;
    color : white;
  }
</style>