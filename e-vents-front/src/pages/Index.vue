<template>
  <Layout>
    <v-container>
      <v-row>
        <v-col sm="6" offset="3">
          <v-tabs v-model="value">
            <v-tab>item one</v-tab>
            <v-spacer></v-spacer>
            <v-tab>item two</v-tab>
            <v-spacer></v-spacer>
            <v-tab>item three</v-tab>
          </v-tabs>
        </v-col>
      </v-row>
    </v-container>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!",
  },
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
