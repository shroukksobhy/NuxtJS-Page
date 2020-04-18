<template>
  <div>
    <h1>Home Page</h1>
    <p>Welcome to my nuxtJS Single Page</p>

    <no-ssr placeholder="Loading...">
      <youtube
        @ready="ready"
        :player-vars="{ autoplay: 1 }"
        :player-width="500"
        :player-height="200"
        :video-id="M7lc1UVf-VE"
      />
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/zuOUN-VSI40"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/ZGb6xasktBg"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>

      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/SzJ46YA_RaA"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/tCAt8eEKPDc"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/ZGb6xasktBg"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </no-ssr>
  </div>
</template>
<script>
export default {
  data() {
    return {
      videos: []
    };
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