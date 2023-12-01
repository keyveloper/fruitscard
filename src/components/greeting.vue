<template>
  <div>
    <h2>{{ greeting }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      greeting: "Hello",
      message: "Welcome to test world!",
    };
  },
};
</script>
