<template>
  <v-app id="inspire">
    
    <!-- naviagtion drawer starts -->

    <v-navigation-drawer v-model="drawer"
      app>
      <v-list-item>
        <v-list-item-content>
          <v-list-item-title class="text-h6">
            Kshitij App
          </v-list-item-title>
          <v-list-item-subtitle>
            API Integration
          </v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-divider></v-divider>

      <v-list
        dense
        nav
      >
        <v-list-item
          v-for="item in items"
          :key="item.title"
          link
        >
          <v-list-item-icon>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>{{ item.title }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>

    <!-- naviagtion drawer ends -->

    <v-app-bar app>
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>

      <v-toolbar-title>Application</v-toolbar-title>
    </v-app-bar>

    <v-main>
      <!--  -->
    </v-main>
  </v-app>
</template>

<script>
  export default {
    // data: () => ({
    //    drawer: null,
    //    items: [
    //       { title: 'Dashboard', icon: 'mdi-view-dashboard' },
    //       { title: 'Photos', icon: 'mdi-image' },
    //       { title: 'About', icon: 'mdi-help-box' },
    //     ], 
    //    }),
  

  data () {
      return {
        drawer: null,
        items: [
          { title: 'Dashboard', icon: 'mdi-view-dashboard' },
          { title: 'Photos', icon: 'mdi-image' },
          { title: 'About', icon: 'mdi-help-box' },
        ],
        // right: null,
      }
    }


  }
</script>