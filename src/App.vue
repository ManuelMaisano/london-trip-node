<template>
  <HeaderComponent />
  <MainComponent />
  <FooterComponent />
</template>

<script>

import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
  export default {
    name: 'App',
    components:{
      MainComponent,
      FooterComponent,
      HeaderComponent
  }
}
</script>

<style lang="scss" scoped>
/* Add your SCSS styles here */
</style>
