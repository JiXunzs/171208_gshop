<template>
    <div>
      <router-view></router-view>
      <FooterGuide v-show="$route.meta.showFooter"></FooterGuide>
    </div>
</template>

<script>
  import FooterGuide from './components/FooterGuide/FooterGuide.vue'
  export default {
    name: 'Vue',
    components:{
      'FooterGuide': FooterGuide
    }
  }
</script>

<style>

</style>
