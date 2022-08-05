<template>
  <div class="home">
    <NavBar />
<!--    <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <ShaoJi/>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue'
import ShaoJi from "@/views/ShaoJi";

export default {
  name: 'HomeView',
  components: {
    ShaoJi,
    NavBar
  }
}
</script>
