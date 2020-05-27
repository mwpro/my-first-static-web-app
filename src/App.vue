<template>
  <div>Hello {{ value }}, hmm, I'm on branch?</div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World"
    };
  }
};
</script>
