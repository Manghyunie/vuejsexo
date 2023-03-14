<template>
  <div id="app">
    <div>My little to do list</div>
    <todo-list />
  </div>
</template>

<script>
import TodoList from './components/TodoList.vue';
export default {
  name: "app",
  components: {
    TodoList
  }
};
</script>

<style>
#app {
  color: #2c3e50;
  margin-top: 5px;
  background-color: #56b0ee;
}
</style>