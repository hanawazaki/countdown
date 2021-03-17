<template>
  <div class="home">
    <h3>Hello World</h3>
    <Counter
      :year="2021"
      :month="4"
      :date="12"
      :hour="24"
      :minute="59"
      :second="59"
      :milisecond="59"
    />
  </div>
</template>

<script>
// @ is an alias to /src
import Counter from "@/components/Counter.vue";

export default {
  name: "Home",
  components: {
    Counter,
  },
};
</script>
