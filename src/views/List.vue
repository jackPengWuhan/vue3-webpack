<template>
  <div class="list">
    <todo-item v-for="item of list" :key="item" :item="item"></todo-item>
  </div>
</template>

<script>
import TodoItem from "../components/TodoItem.vue";
export default {
  components: { TodoItem },
  name: "todo-list",
  data() {
    return {
      list: ["eat", "play", "sleep", "run"],
    };
  },
};
</script>
<style lang="scss" scoped>
.list {
  background-color: aliceblue;
}
</style>