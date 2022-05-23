<template>
  <div id="app">
    <header-com></header-com>
    <todo-app></todo-app>
    <modal-test></modal-test>
  </div>
</template>

<script>
import TodoApp from "./components/TodoApp.vue";
import HeaderCom from "./components/HeaderCom.vue";
import ModalTest from "./components/ModalTest.vue";
export default {
  name: "App",
  components: {
    TodoApp,
    HeaderCom,
    ModalTest,
  },
};
</script>

<style>
body {
  overflow-x: hidden;
}
</style>
