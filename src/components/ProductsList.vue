<template>
  <v-container fluid fill-height class="back-panel" grid-list-xl d-flex>
    <v-layout row wrap>
     <v-flex xs11 my-5 style="margin: 0 auto;">
      <v-layout row wrap align-center>
            <v-flex v-for="n in 12" :key="n" xs3 md4 my-5>
                <product-card />
            </v-flex>
      </v-layout>
     </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'ProductsList'
};
</script>

<style scoped>
.back-panel {
  background: url('../assets/background.jpg');
  background-size: cover;
  width: 100%;
  height: 100%;
}

</style>
