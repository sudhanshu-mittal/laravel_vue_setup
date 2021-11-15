<template>
  <h1>{{ greeting }}</h1>
  <h2>{{ message }}</h2>
  <h3 style="font-family: bold; color: red">Yeah!!!</h3>
</template>
<script>
export default {
  setup: () => ({
    greeting: "Hello World from Vue 3!",
    message: "Your techSam is here for you!",
  }),
};
</script>
