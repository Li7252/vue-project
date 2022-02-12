<template>
  <div>
    <Banner />
    <h1>{{massage}}</h1>
  </div>
</template>

<script>
import Banner from '../components/Home/Banner.vue'
  export default { 
    data() {
      return {
        massage: 'Hello World'
      }
    },
    components: {Banner}    
  }
</script>

<style lang="css" scoped>

</style>