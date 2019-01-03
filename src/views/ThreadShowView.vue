<template>
  <TreadShow />
</template>
<script>
import TreadShow from '../components/ThreadShow'
export default {
  name: 'ThreadShowView',
  props: {
    id: {
      required: true,
      type: String
    }
  },
  components: {
    TreadShow
  }
}
</script>
