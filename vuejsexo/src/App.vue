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
  color: #ffffff;
  margin-top: 5px;
  background-color: #671c6c;
}
</style>