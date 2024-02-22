<template>
  <div>
    <h2 :class="titleClass">{{ title }}</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
        titleClass: 'title-style',
    };
  },
  props: {
    title: {
        type: String,
        required: true,
    }
  }
};
</script>

<style scoped>
h2 {
    color: white;
    font-family: "Montserrat", sans-serif;
    font-size: 3rem;
    letter-spacing: 5px;
}
</style>
