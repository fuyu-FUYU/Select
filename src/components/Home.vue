<template>
  <div>
    <!-- 向Input进行传值 -->
    <Input v-bind:subject="subject" />
  </div>
</template>

<script>
import Input from "@/views/aa.vue";
export default {
  name: "App",
  components: {
    Input
  },
  data() {
    return {
      subject: [
        {
          value: "1",
          text: "111"
        },
         {
          value: "2",
          text: "222"
        },
        {
          value: "3",
          text: "333"
        },
        {
          value: "4",
          text: "444"
        }
      ]
    };
  }
};
</script>