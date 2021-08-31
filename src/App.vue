<template>
  <todo-list></todo-list>
</template>
<script>
import TodoList from "./views/List.vue";

export default {
  components: { TodoList },
  name: "app",
  data() {
    return {};
  },
};
</script>