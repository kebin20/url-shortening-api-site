<template>
  <v-menu>
    <template v-slot:activator="{ props }">
      <v-btn elevation="0" icon="mdi-menu" v-bind="props"></v-btn>
    </template>
    <v-list class="list">
      <v-list-item v-for="(item, i) in items" :key="i">
        <v-list-item-title class="text-center">{{ item.title }}</v-list-item-title>
      </v-list-item>
      <v-divider></v-divider>
      <v-container class="d-flex flex-column align-center">
        <v-button class="px-4 py-2">Login</v-button>
        <v-button class="px-4 py-2">Sign Up</v-button>
      </v-container>
    </v-list>
  </v-menu>
</template>

<script>
export default {
  data: () => ({
    items: [{ title: 'Features' }, { title: 'Pricing' }, { title: 'Resources' }]
  })
}
</script>

<style>
.list {
  top: 30px;
  width: 20.4em;
}
</style>