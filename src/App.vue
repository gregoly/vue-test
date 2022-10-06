<template>
  <div id="app">
    <app-header />
    <app-content />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppContent from "./components/AppContent.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppContent
},
};
</script>
