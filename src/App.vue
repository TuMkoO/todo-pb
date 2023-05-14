<template>
  <AppHeader />

  <AppFilters />

  <main class="app-main">
    <AppTodoList />

    <AppAddTodo />
  </main>

  <AppFooter />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import AppHeader from "./components/AppHeader.vue";
import AppFilters from "./components/AppFilters.vue";
import AppAddTodo from "./components/AppAddTodo.vue";
import AppTodoList from "./components/AppTodoList.vue";
import AppFooter from "./components/AppFooter.vue";

export default defineComponent({
  components: { AppHeader, AppFilters, AppAddTodo, AppTodoList, AppFooter },
});
</script>

<style scoped></style>
