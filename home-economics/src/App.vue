<template>
  <v-app>
    <v-main>
       <v-card
         class="d-flex justify-center mb-6"
         :color="$vuetify.theme.dark ? 'grey darken-3' : 'grey lighten-4'"
         flat
         tile
       >
         <router-link to="/about">about</router-link>
         <router-link to="/">  Home</router-link>
       </v-card>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
