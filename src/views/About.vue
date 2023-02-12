<template>
  <div>
    <h1>About</h1>
    <p>This is an about page</p>
    <!-- <span v-text="msg"></span> -->
    <!-- same as -->
    <span>{{ msg }}</span>
    <button @click="changeMsg()">change</button>

    <router-link to="/">
      <button>Go to Home</button>
    </router-link>
  </div>
</template>
<script>
export default {
  name: "About",
  data() {
    return {
      msg: "Hello world",
    };
  },
  methods: {
    changeMsg() {
      this.msg = "Hello world again";
    },
  },
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
