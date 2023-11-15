<template>
    <v-container fluid>
      <v-row>
        <v-col cols="12" md="3">
          <Sidebar />
        </v-col>
        <v-col cols="12" md="9">
          <v-card>
            <v-card-title>About</v-card-title>
            <v-card-text>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam
                voluptate, quibusdam, voluptatum, quia voluptas quod voluptatem
                voluptatibus quos doloribus quae quidem. Quisquam, voluptate
                voluptatibus. Quisquam, voluptate voluptatibus.
              </p>
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-container>  

  </template>
  
  <script>

  import Sidebar from '../components/Sidebar.vue'

  export default {
    components: {
      Sidebar
    },
     
    data() {
      return {
        //
      }
    },
    methods: {
      //
    }
  }
  </script>
  
  <style scoped>
  /* Add your CSS here */
  </style>