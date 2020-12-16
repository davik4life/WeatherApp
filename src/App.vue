<template>
  <h1 class="title">Weather App</h1>
  <input class="searchbox" @click="searching" placeholder="Weather Search..." />
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      searching() {},
    };
  },
};
</script>

<style>
.title {
  display: flex;
  justify-content: center;
}
.searchbox {
  display: flex;
  justify-content: center;
  /* align-items: center; */
  /* box */
}
</style>
