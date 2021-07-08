<template>
  <div class="home">
    <h1>Main component</h1>
    <childcomponent1 />
    <childcomponent2 />
    <Childcomponent3 />
    <Childcomponent4 />
    <databinding />
  </div>
</template>

<script>
import Childcomponent1 from "./Childcomponent1.vue";
import Childcomponent2 from "./Childcomponent2.vue";
import Childcomponent3 from "./Childcomponent3.vue";
import Childcomponent4 from "./Childcomponent4.vue";
import Databinding from "./Databinding.vue";
export default {
  name: "Home",
  components: {
    Childcomponent1,
    Childcomponent2,
    Childcomponent3,
    Childcomponent4,
    Databinding,
  },
};
</script>

<style scoped>
.home {
  background-color: rgb(231, 119, 119);
  font-family: fantasy;
  color: rgb(105, 48, 8);
  margin: 0%;
  padding: 0%;
}
</style>