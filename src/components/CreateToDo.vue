<template>
  <v-container>
    <v-row justify="center">
      <v-col cols="4">
        <v-text-field v-model="todo" label="Task" solo></v-text-field>
      </v-col>
      <v-col class="pt-2" cols="1">
        <v-btn icon x-large><v-icon>mdi-plus-circle</v-icon></v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style></style>
