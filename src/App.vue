<template>
  <v-app>
     <v-app-bar app color="primary" dark>
      <v-toolbar-title>Example website using Vuetify</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn text rounded to="/">Home</v-btn>
      <v-btn text rounded to="/login">Login</v-btn>
    </v-app-bar>
    <v-content>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: 'App',
};
</script>
