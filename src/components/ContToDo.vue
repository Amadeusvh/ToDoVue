<template>
  <v-container>
    <v-row justify="center">
      <v-col align="center">
        <create-to-do />
      </v-col>
    </v-row>
    <v-divider></v-divider>
    <v-row justify="center">
      <v-col align="center" cols="6">
        <to-do />
        <to-do />
        <to-do />
        <to-do />
        <to-do />
        <to-do />
        <to-do />
        <to-do />
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import CreateToDo from "./CreateToDo.vue";
import ToDo from "./ToDo.vue";
export default {
  components: { CreateToDo, ToDo },
};
</script>

<style></style>
