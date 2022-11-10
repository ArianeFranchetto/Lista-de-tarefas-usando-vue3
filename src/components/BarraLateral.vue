<template>
  <header>
    <h1>
      <img src="../assets/logo.png" alt="Logo do site">
    </h1>
    <div class="section">
    <Section/>
  </div>

  </header>




</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Section from './Section.vue';

export default defineComponent({
  name: 'BarraLateral',


  components: {
    Section
  }


})
</script>

<style scoped>
header {
  padding: 1rem;
  background: #ee82ee;
  width: 100%;
  height: 100vh;
}

.section {
  background-color: blanchedalmond;
  border-radius: 50px;
  margin-top: 4rem;
  
}

@media only screen and (max-width: 768px) {
  header {
    padding: 2.5rem;
    height: auto;
  }
}
</style>