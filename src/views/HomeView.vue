<template>
  <div>
    <Navbar msg="Welcome to Your Vue.js App" />
    <div class="container mt-50">
      <h2>Welcome to Nas Restaurant</h2>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'HomeView',
  components: {
    Navbar,
  },
}
</script>
