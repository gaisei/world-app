<template>
  <section>
    <div class="country-list">
      <nuxt-link to="/country">
        <div class="country-item">
          <p class="country-image"><img src="@/assets/images/usa/top.jpg" alt=""></p>
          <p class="country-name">アメリカ</p>
        </div>
      </nuxt-link>
      <div class="country-item">
        <p class="country-image"><img src="@/assets/images/usa/top.jpg" alt=""></p>
        <p class="country-name">イギリス</p>
      </div>
      <div class="country-item">
        <p class="country-image"><img src="@/assets/images/usa/top.jpg" alt=""></p>
        <p class="country-name">フランス</p>
      </div>
      <div class="country-item">
        <p class="country-image"><img src="@/assets/images/usa/top.jpg" alt=""></p>
        <p class="country-name">ドイツ</p>
      </div>
      <div class="country-item">
        <p class="country-image"><img src="@/assets/images/usa/top.jpg" alt=""></p>
        <p class="country-name">オランダ</p>
      </div>
      <div class="country-item">
        <p class="country-image"><img src="@/assets/images/usa/top.jpg" alt=""></p>
        <p class="country-name">ベルギー</p>
      </div>
      <div class="country-item">
        <p class="country-image"><img src="@/assets/images/usa/top.jpg" alt=""></p>
        <p class="country-name">ポーランド</p>
      </div>
      <div class="country-item">
        <p class="country-image"><img src="@/assets/images/usa/top.jpg" alt=""></p>
        <p class="country-name">チェコ</p>
      </div>
      <div class="country-item">
        <p class="country-image"><img src="@/assets/images/usa/top.jpg" alt=""></p>
        <p class="country-name">ハンガリー</p>
      </div>
      <div class="country-item">
        <p class="country-image"><img src="@/assets/images/usa/top.jpg" alt=""></p>
        <p class="country-name">オーストリア</p>
      </div>
      <div class="country-item">
        <p class="country-image"><img src="@/assets/images/usa/top.jpg" alt=""></p>
        <p class="country-name">イタリア</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.country-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.country-item {
  width: 300px;
  text-align: center;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
  margin: 20px;
}
</style>