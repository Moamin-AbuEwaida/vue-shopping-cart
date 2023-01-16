<template>
  <v-app :style="{ background: $vuetify.theme.themes.dark.background }">
    <sideBar />
  </v-app>
</template>

<script>
import SideBar from "../components/SideBar.vue";
export default {
  name: "HomePage",

  components: { SideBar },
};
</script>
