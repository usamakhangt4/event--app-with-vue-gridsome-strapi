<template>
  <v-app class="layout">
    <v-app-bar color="blue" app dark>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-toolbar-title>E-vents</v-toolbar-title>
      <v-text-field
        placeholder="Search"
        class="ml-8"
        style="max-width:350px"
        outlined
        rounded
        dense
        hide-details
        prepend-inner-icon="mdi-magnify"
      ></v-text-field>
      <v-spacer></v-spacer>
      <v-btn small elevation color>Create Event</v-btn>
    </v-app-bar>
    <v-main>
      <slot />
    </v-main>
  </v-app>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

