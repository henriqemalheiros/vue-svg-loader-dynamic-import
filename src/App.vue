<template>
  <div>
    <DynamicIcon icon="mood_bad"/>
    <DynamicIcon icon="mood"/>
  </div>
</template>

<script>
import DynamicIcon from './components/DynamicIcon.vue'

export default {
  name: 'IconList',
  components: {
    DynamicIcon
  }
}
</script>
