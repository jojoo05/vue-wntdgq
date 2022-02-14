<template>
  <div id="raten">
    <h2>{{ masg }}</h2>
    <input v-model.number="unserVariablenName" />
    <h3>{{ unserVariablenName }}</h3>
  </div>
</template>

<script>
export default {
  name: 'Raten',
  data: () => {
    return {
      unserVariablenName: 0,
    };
  },
  props: {
    msg: String,
  },
};
</script>

<style scoped></style>
