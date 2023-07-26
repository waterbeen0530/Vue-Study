<template>
  <div class="rootContainer">
    <div class="container">
      <headerIndex />
    </div>
  </div>
</template>

<script>
import HeaderIndex from "./components/common/header/index.vue";

export default {
  name: "App",
  components: {
    HeaderIndex,
  },
};
</script>

<style scoped>
.rootContainer {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.container {
  width: 1200px;
}
</style>
