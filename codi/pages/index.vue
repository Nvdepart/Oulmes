<template>
  <v-app>
    <!-- Add the hero image of the Oulmes Fortress -->
    <div class="hero-image">
      <v-img
        src="https://agadirmichelterrier.files.wordpress.com/2023/02/image-121.png"
        height="100%"
      ></v-img>
    </div>

    <!-- Add the container for the content -->
    <v-container class="pa-5">
      <!-- Add the brief introduction to the city -->
      <v-card class="city-info">
        <v-card-title class="text-center mb-5"
          >Welcome to Oulmes, Morocco</v-card-title
        >
        <v-card-text>
          <p>
            Oulmes is a city located in the province of Khouribga in central
            Morocco. The city has a rich history and culture, with many historic
            landmarks and cultural sites to visit.
          </p>
          <p>
            Some of the popular tourist attractions in Oulmes include the Oulmes
            Fortress, the Souk, and the Hassan El Glaoui Museum. The city is
            also known for its traditional cuisine, including dishes such as
            tagine and couscous.
          </p>
          <p>
            Explore the beauty and charm of Oulmes, Morocco and immerse yourself
            in the city's unique culture and heritage.
          </p>
        </v-card-text>
      </v-card>
    </v-container>
  </v-app>
</template>

<script>
export default {
  name: "HomePage",
};
</script>

<style scoped>
/* Add some basic styles for the page */
.hero-image {
  height: 400px;
  position: relative;
  overflow: hidden;
}

/* Style the image */
.hero-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

/* Style the brief introduction to the city */
.city-info {
  background-color: #f5f5f5;
  border-radius: 10px;
  max-width: 800px;
  margin: 0 auto;
  box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.2);
}

/* Add some spacing between the paragraphs */
.city-info p {
  margin: 20px 0;
}
</style>
