<template>
  <v-col cols="12" sm="4">
    <v-card color="#03A9F4" class="card">
      <div style="text-align: center;">
        <p class="display-3 white--text font-weight-bold">{{ title }}</p>
      </div>
      <v-card-text class="white--text">{{ body }}</v-card-text>
    </v-card>
  </v-col>
</template>

<style lang="scss">
  .card {
    padding-top: 32px;
  }
</style>

<script>
export default {
  props: {
    title: String,
    body: String
  }
}
</script>
