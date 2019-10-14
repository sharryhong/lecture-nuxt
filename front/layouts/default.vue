<template>
  <v-app>
    <v-toolbar>
      <v-toolbar-title>
        <v-btn text nuxt to="/">Home</v-btn>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-text-field />
        <v-btn text nuxt to="/profile">Profile</v-btn>
        <v-btn text nuxt to="/signup">Signup</v-btn>
      </v-toolbar-items>

    </v-toolbar>
  </v-app>
</template>

<script>
export default {
}
</script>

<style scoped>
</style>
