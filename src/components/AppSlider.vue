<template>
  <div class="slider"></div>
</template>

<script>
export default {
  name: "AppSlider",
  data() {
    return {
      slides: [
        "https://iso.500px.com/wp-content/uploads/2014/10/2048-51.jpg",
        "https://images2.minutemediacdn.com/image/upload/c_crop,h_1613,w_2400,x_0,y_17/v1572194246/shape/mentalfloss/87226-gettyimages-537121731.jpg?itok=RQxqLlyM",
        "https://thenypost.files.wordpress.com/2015/10/shutterstock_90194617.jpg?quality=80&strip=all",
      ],
    };
  },
};
</script>

<style>
.slider {
  height: 100vh;
  background-color: #ccc;
}
</style>
