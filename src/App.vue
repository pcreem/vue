<!-- ./src/App.vue -->
<template>
  <div id="restaurant-forum">
    <Navbar />
    <main role="main" class="mt-5 bg-white">
      <router-view />
    </main>
  </div>
</template>

<script>
// ./src/App.vue
import "bootstrap";
import "bootstrap/dist/css/bootstrap.min.css";
import Navbar from "./components/Navbar";

export default {
  components: {
    Navbar
  }
};
</script>