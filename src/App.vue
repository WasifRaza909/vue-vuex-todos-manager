<template>
  <div id="app">
    <div class="container">
      <AddTodoComponent />
      <FilterTodosComponent />
      <TodosComponent />
    </div>
  </div>
</template>

<script>
import TodosComponent from "./components/TodosComponent.vue";
import AddTodoComponent from "./components/AddTodoComponent.vue";
import FilterTodosComponent from "./components/FilterTodosComponent.vue";

export default {
  name: "App",
  components: {
    TodosComponent,
    AddTodoComponent,
    FilterTodosComponent,
  },
};
</script>

<style>
body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
