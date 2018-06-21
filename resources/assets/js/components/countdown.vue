<template>
  <div>
    <!-- <Countdown deadline="August 22, 2022"></Countdown> -->
    <!-- or  -->
    <Countdown end="October 1, 2018"></Countdown>
    
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
  color:#E53935;
  font-size: 50px !important;
}
.text{
  font-weight: bolder
}
</style>
