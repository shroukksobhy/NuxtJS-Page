<template>
  <div id="player">
    <h1>Home Page</h1>
    <p>Welcome to my nuxtJS Single Page</p>
  </div>
</template>
<script>
import axios from "axios";
export default {
  data() {
    return {
      videos: []
    };
  },
  async created() {
    const config = {
      headers: {
        Accept: "application/json"
      }
    }; 
  try{
    const res = s;
  } catch (error) {
    console.log(error);
  }
  },
  head() {
    return {
      title: "Home Page",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "This is my first work in nuxt JS"
        }
      ]
    };
  }
};

</script>
<style>
</style>