<template>
<v-card>
    <v-layout>
      <v-navigation-drawer
        floating
        permanent
      >
        <v-list
          density="compact"
          nav
        >
          <v-list-item prepend-icon="mdi-view-dashboard" title="Home" value="home"></v-list-item>
          <v-list-item prepend-icon="mdi-account" title="Profile" value="profile"></v-list-item>
          <v-list-item prepend-icon="mdi-forum" title="About" value="about"></v-list-item>
            <v-list-item prepend-icon="mdi-settings" title="Settings" value="settings"></v-list-item>
            <v-list-item prepend-icon="mdi-logout" title="Logout" value="logout"></v-list-item>

        </v-list>
      </v-navigation-drawer>
      <v-main style="height: 250px"></v-main>
    </v-layout>
  </v-card>
</template>

<script>
export default {
    name: "Sidebar",

    data() {
        return {
            
        };
    },
    methods: {
        
    },
};
</script>

<style scoped></style>
