<template>
  <v-app>
    <v-main>
      <h1>Estou brilhando</h1>
      <to-do-header />
      <to-do-title />
      <cont-to-do />
    </v-main>
  </v-app>
</template>

<script>
import ContToDo from "./components/ContToDo.vue";
import ToDoHeader from "./components/ToDoHeader.vue";
import ToDoTitle from "./components/ToDoTitle.vue";

export default {
  name: "App",

  components: {
    ToDoTitle,
    ToDoHeader,
    ContToDo,
  },

  data: () => ({
    //
  }),
};
</script>
