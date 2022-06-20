<template>
  <div>

    <PageTitle></PageTitle>
    
    <BgHero></BgHero>
    
  </div>
</template>

<script>
import PageTitle from './components/PageTitle.vue'
import BgHero from './components/BgHero.vue'


export default {
  name: 'App',
  data(){
    
  },
  components:{
    PageTitle,
    BgHero,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

body{
  margin: 0;
}
</style>
