<template>
  <v-container fluid fill-height class="home-panel" style="max-height: 100vh;">
    <v-layout justify-center align-center column pa-5>
      <div class="display-4 font-weight-black black--text text-xs-center">
        SHOWCASE DEMO APP
      </div>
      <div class="display-4 font-weight-black black--text text-xs-center mb-3">
        AS POLYGOT MICROSERVCICES
      </div>
      <div class="display-1 font-weight-bold black--text text-xs-center">
        shows various metrics and concerns.
      </div>
      <v-btn fab class="mt-5 brown darken-4">
        <v-icon large color="white">expand_more</v-icon>
      </v-btn>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'HomePanel'
};
</script>

<style scoped>
.home-panel {
  background: url('../assets/background.jpg');
  background-size: cover;
  width: 100%;
  height: 100%;
}
</style>
