<template>
  <div class="wrap">
    <div class="account-info">
      <img src="~assets/img/IMG_2055.JPG" alt="画像" class="account-img">
      <div class="text">
        <p class="account">趣味：カフェ巡り、筋トレ</p>
        <p>アカウント名</p>
      </div>
    </div>
    <img src="~assets/img/4620693218524983817.ebd4d7254e2d1b3e2794235ec3e0dbad.20032202.jpg" alt="画像" class="main-img">
  </div>
</template>

<script>
import { ContentLoader } from 'vue-content-loader'

export default {
  components: {
    ContentLoader 
  }
}
</script>

<style scoped>
.wrap {
  display: flex;
  flex-direction: column;
  height: 700px;
  width: 600px;
  margin: 30px auto;
}
.account-info {
  display: flex;
}
.account-img {
  height: 70px;
  width: 70px;
  border-radius: 50%;
}
.text {
  height: 70px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: left;
  margin-left: 40px;
}
.account {
  font-size: 20px;
}
.main-img {
  margin-top: 20px;
  height: 500px;
  width: 475px;
  border-radius: 5px;
}
</style>