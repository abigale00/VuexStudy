<template>
  <div>
    hello world.
    <hr />
    <span>加法组件</span>
    <addition-vue></addition-vue>
    <span>减法组件</span>
    <subtraction-vue></subtraction-vue>
  </div>
</template>

<script>
import AdditionVue from "./components/Addition.vue";
import SubtractionVue from "./components/Subtraction.vue";

export default {
  data() {
    return {};
  },
  components: {
    SubtractionVue,
    AdditionVue,
  },
};
</script>
