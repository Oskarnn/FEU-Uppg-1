<script>
export default {
  data() {
    return {
      date: "2023-02-08",
    };
  },
};
</script>

<template>
  <div>
    <p>Skapad av Oskar Nygren</p>
    <p>{{ date }}</p>
  </div>
</template>

<style scoped>
div {
  background-color: rgba(0, 0, 0, 0.1);
  display: flex;
  justify-content: space-evenly;
  margin-top: 100%;
}
</style>
