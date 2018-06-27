<template>
  <p>Hello {{ pilot }}!</p>
  <cockpit-component />
</template>

<script>
import CockpitComponent from './CockpitComponent.vue'

module.exports = {
  name: 'Millenium Falcon',
  data: function() {
    return {
      pilot: 'Chewbacca'
    }
  },
  components: {
    CockpitComponent
  }
}
</script>

<style scoped>
p {
  font-size: 32px;
  text-align: center;
}
</style>
