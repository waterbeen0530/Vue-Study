<template>
  <div class="container">
    <div class="wrapper">
      <img id="logo" src="../../../assets//imgs/header/chaneat.png" alt="" />
      <div class="navBox">
        <p class="navText">랜덤 메뉴 추천</p>
        <p class="navText">메뉴 MBTI</p>
        <p class="navText">오늘의 메뉴</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "headerIndex",
};
</script>

<style scoped>
.container {
  width: 100%;
  height: 80px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.wrapper {
  width: 100%;
  height: 80px;
  gap: 60px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}

#logo {
  width: 82px;
}

.navBox {
  gap: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.navText {
  font-size: 16px;
  font-weight: 600;
}
</style>
