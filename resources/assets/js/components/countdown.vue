<template>
  <div>
    <!-- <Countdown deadline="August 22, 2022"></Countdown> -->
    <!-- or  -->
    <Countdown end="August 26, 2018"></Countdown>
    
  </div>
</template>

<script>
import Countdown from 'vuejs-countdown'

export default {
  components: { Countdown }
}
</script>

<style>

.digit{
  color:#cddc39;
  font-size: 50px !important;
}
.text{
  font-weight: bolder
}
</style>
