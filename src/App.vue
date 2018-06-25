<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <commen-header></commen-header>
    <router-view/>
    <commen-footer></commen-footer>
  </div>
</template>

<script>
import CommonHeader from '@/components/common/Header'
import CommonFooter from '@/components/common/Footer'
export default {
  name: 'App',
  components:{
    CommonHeader,
    CommonFooter
  }
}
</script>

<style>

</style>
