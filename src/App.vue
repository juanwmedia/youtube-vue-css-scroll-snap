<template>
  <div id="app">
    <AppSlider :slides="slides" />
  </div>
</template>

<script>
import AppSlider from "./components/AppSlider.vue";
export default {
  name: "App",
  data() {
    return {
      slides: [
        {
          image: "https://iso.500px.com/wp-content/uploads/2014/10/2048-51.jpg",
          text: "Black Cats"
        },
        {
          image: "https://images2.minutemediacdn.com/image/upload/c_crop,h_1613,w_2400,x_0,y_17/v1572194246/shape/mentalfloss/87226-gettyimages-537121731.jpg?itok=RQxqLlyM",
          text: "Are"
        },
        {
          image: "https://thenypost.files.wordpress.com/2015/10/shutterstock_90194617.jpg?quality=80&strip=all",
          text: "Awesome 😸"
        }
      ],
    };
  },
  components: {
    AppSlider,
  },
};
</script>

<style>
html,
body {
  height: 100%;
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
