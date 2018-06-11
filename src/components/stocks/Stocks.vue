<template>
  <div>
    <app-stock v-for="test in tests"></app-stock>
  </div>
</template>

<script>
import Stock from "./Stock.vue";

export default {
  data: function() {
    return {
      tests: [1, 2, 3, 4]
    };
  },
  components: {
    appStock: Stock
  }
};
</script>
