<template>
  <div id="app">
    <InboxScreen />
  </div>
</template>

<script>
  import InboxScreen from "./components/InboxScreen.vue";
  // import TaskList from "./components/TaskList.vue";

  export default {
    name: "App",
    components: {
      InboxScreen,
      // TaskList,
    }
  };
</script>

<style>
  @import "./index.css";
</style>