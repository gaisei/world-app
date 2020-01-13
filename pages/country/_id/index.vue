<template>
  <div>
    <Header />
    {{ spotName }}
  </div>
</template>

<script>
import Header from '@/components/Header'

export default {
  data() {
    return {
      spotName: '自由の女神'
    }
  },
  components: {
    Header
  }
}
</script>