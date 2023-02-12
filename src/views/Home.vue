<template>
  <div>
    <h1>Home</h1>
    <p>This is an Home page</p>
    <router-link to="/about">
      <button>Go to About</button>
    </router-link>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped>
button {
  padding: 10px;
  border: none;
  color: white;
  background-color: green;
  border-radius: 5px;
  cursor: pointer;
}
</style>
