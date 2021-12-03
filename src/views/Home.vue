<template>
  <div id="chart" class="home">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
     <apex-chart />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import ApexChart from '../components/ApexChart.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
    ApexChart
  }
}
</script>
