<template>
  <button class="feedback-btn">
    {{ buttonText }}
  </button>
</template>

<script>
export default {
  name: "Button",
  props: {
    buttonText: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
.feedback-btn {
  background-color: #000000;
  color: #00ff00;
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  cursor: pointer;
}

.feedback-btn:hover {
  background-color: #333333;
}
</style>
