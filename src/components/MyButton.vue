<template>
  <div>
    <button>
      Hello
    </button>
    <p class="violet">{{ msg }}</p>
    <b-button variant="success">Button</b-button>
  </div>
</template>

<script>
export default {
  name: "my-button",
  data() {
    return {
      msg: "My button",
    };
  },
};
</script>

<style scoped>
button {
  color: red;
}
p.violet {
  color: violet;
}
</style>
