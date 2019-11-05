<template>
  <v-app>
    <v-app-bar app>
      <Header/>
    </v-app-bar>
    <v-content>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>
import Header from "@/components/Header";
export default {
  name: "App",
 
  components: {
     Header
  }
};
</script>
