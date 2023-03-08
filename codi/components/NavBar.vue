<template>
  <v-app-bar app color="primary" dark>
    <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
    <v-toolbar-title>Oulmes</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-navigation-drawer v-model="drawer" app temporary>
      <v-list>
        <v-list-item to="/" exact>
          <v-list-item-icon>
            <v-icon>mdi-home</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Home</v-list-item-title>
        </v-list-item>
        <v-list-item to="/things-to-do">
          <v-list-item-icon>
            <v-icon>mdi-map-marker-multiple</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Things to Do</v-list-item-title>
        </v-list-item>
        <v-list-item to="/where-to-eat">
          <v-list-item-icon>
            <v-icon>mdi-food</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Where to Eat</v-list-item-title>
        </v-list-item>
        <v-list-item to="/accommodations">
          <v-list-item-icon>
            <v-icon>mdi-hotel</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Accommodations</v-list-item-title>
        </v-list-item>
        <v-list-item to="/history">
          <v-list-item-icon>
            <v-icon>mdi-book</v-icon>
          </v-list-item-icon>
          <v-list-item-title>History</v-list-item-title>
        </v-list-item>
        <v-list-item to="/local-businesses">
          <v-list-item-icon>
            <v-icon>mdi-domain</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Local Businesses</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
  </v-app-bar>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      drawer: false,
    };
  },
};
</script>
