<template>
  <div>
    <Header />
    <h1>{{ countryName }}</h1>
    <div class="country-spot-list">
      <nuxt-link to="/country/1">
        <div class="country-spot-item">
          <p class="country-spot-image"><img src="@/assets/images/usa/1.jpg" alt=""></p>
          <p class="country-spot-name">自由の女神</p>
        </div>
      </nuxt-link>
    </div>
  </div>
</template>

<script>
import Header from '@/components/Header'

export default {
  data() {
    return {
      countryName: 'アメリカ'
    }
  },
  components: {
    Header
  }
}
</script>