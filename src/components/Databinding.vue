<template>
  <div class="bind">
    <h1>Data Binding</h1>
    <p>Type here to see changes and press enter</p>
    <h1 style="white-space: pre-line">{{ message }}</h1>
    <textarea type="text" v-model="message" />
  </div>
</template>

<script>
export default {
  name: "Databinding",
  data() {
    return {
      message: "hey",
    };
  },
};
</script>

<style scoped>
.bind {
  color: crimson;
  background-color: cyan;
}
</style>