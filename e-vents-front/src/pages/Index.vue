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
          <v-card>
            <v-card-media class="red--text" src="src" height="200px">
              <v-container fill-height fluid>
                <v-layout fill-height>
                  <v-flex xs12 align-end flexbox>
                    <span class="headline">headline</span>
                  </v-flex>
                </v-layout>
              </v-container>
            </v-card-media>
            <v-card-title>
              <div>
                <span class="red--text">text</span>
                <br />
                <span>text</span>
                <br />
                <span>description</span>
              </div>
            </v-card-title>
            <v-card-actions>
              <v-btn flat color="primary">text</v-btn>
              <v-btn flat color="primary">text</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!',
  },
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
