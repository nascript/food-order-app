<template>
  <div>
    <Navbar msg="Welcome to Your Vue.js App" />
    <div class="container mt-10">
      <h2>List of Foods</h2>
    </div>
  </div>
</template>

<!-- eslint-disable vue/multi-word-component-names -->
<script>
import Navbar from '@/components/Navbar.vue'
export default {
  name: 'Foods',
  components: {
    Navbar,
  },
}
</script>

<style></style>
